<template>
  <div class="home">
    <Counter 
    :year= "2023"
    :month= "6"
    :date= "28"
    :hour= "23"
    :minute= "59"
    :second= "59"
    :milisecond= "31"
     />
  </div>
</template>

<script>
// @ is an alias to /src
import Counter from '../components/Counter.vue';

export default {
  name: "Home",
  components: {
    Counter,
  },
};
</script>
