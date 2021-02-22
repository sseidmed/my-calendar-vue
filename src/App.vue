<template>
  <div id="app">
    <CalendarWeek />
    <CalendarEntry />
  </div>
</template>

<script>
import CalendarWeek from './components/CalendarWeek.vue';
import CalendarEntry from './components/CalendarEntry.vue';
export default {
  name: 'App',
  components: {
    CalendarEntry, 
    CalendarWeek
  }
}
</script>

<style scoped>
#app {
  height: 100vh;
  background: #6e6e6e;
  padding-top: 80px;
}


.columns {
  display: grid;
  grid-template-columns: repeat(7, 1fr);
 
}

.day {

  border-right: 1px solid grey;
  background-color: #4A4A4A;
  color: white;
}

.calendar-entry-note {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 20px auto;
  padding: 10px;
  background-color: white;
  width: 25%; 
  border-radius: 10px;
}

span, i {
  color: black;
}

.day-banner {
  margin: auto;
  background-color: #252525;
  text-align: center;
}

.day-number {
  margin: 10px;
}



</style>
