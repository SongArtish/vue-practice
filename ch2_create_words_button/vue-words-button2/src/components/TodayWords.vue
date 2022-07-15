<template>
  <div class="hello">
    <h1>오늘의 말씀을 주시옵소서!</h1>
    <h3 v-if="selectedWord.length">이렇게 살아가길 원합니다.</h3>
  </div>
</template>

<script>
export default {
  name: 'TodayWords',
  data: function () {
    return {
      // words: [],
      // selectedWord: ''
    }
  },
  methods: {
    pick: function () {
    }
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}

#button {
  background-color: #008CBA;
  font-size: 5rem;
  color: white;
  border: solid #008CBA;
  transition-duration: 0.4s;
  cursor: pointer;
}
#button:hover {
  background-color: white;
  color: #008CBA;
}
</style>
