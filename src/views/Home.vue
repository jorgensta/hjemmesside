<template>
  <div class="home">
    <div>RUSTIC RIVERBED</div>
    <div class="first">#2b4d59</div>
    <div class="second">#39998e</div>
    <div class="third">#FFDC7C</div>
    <div class="forth">#FFAA67</div>
    <div class="fifth">#DA674A</div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {}
};
</script>

<style lang="sass">
.home
  display: flex
  justify-content: center
  align-items: center
  flex-direction: column

.first
  width: 320px
  padding: 10px
  border: 5px solid #2b4d59
  margin: 1px
  background-color: #2b4d59
  color: white

.second
  width: 320px
  padding: 10px
  border: 5px solid #39998e
  margin: 1px
  background-color: #39998e

.third
  border: 5px solid #FFDC7C
  margin: 1px
  width: 320px
  padding: 10px
  background-color: #FFDC7C

.forth
  border: 5px solid #FFAA67
  margin: 1px
  width: 320px
  padding: 10px
  background-color: #FFAA67

.fifth
  border: 5px solid #DA674A
  margin: 1px
  width: 320px
  padding: 10px
  background-color: #DA674A
</style>
