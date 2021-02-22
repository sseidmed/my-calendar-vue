<template>
    <div id="calendar-entry">
      <div class="calendar-entry-note">
        <input type="text" placeholder="New Event" />
        <p class="calendar-entry-day">Day of event: <span class="bold">Monday</span></p>
        <a class="button btn btn-info">Submit</a>
      </div>
    </div>
</template>

<script>
    export default {
        name: 'CalendarEntry'
    }
</script>

<style scoped>
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
</style>