<template>
    <div>
    <div id="calendar-week" class="container">
      <div class="columns">
        <div class="day">
          <div class="day-banner">Mon</div>
          <div class="day-details">
            <div class="day-number">1</div>
            <div class="day-event" style="background-color: rgb(153, 255, 153)">
              <div>
                <span>Get Groceries</span> 
                <div><i class="fa fa-pencil-square edit-icon"></i> 
                  <i class="fa fa-trash-o delete-icon"></i>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="day">
          <div class="day-banner">Tue</div>
          <div class="day-details">
            <div class="day-number">2</div>
          </div>
        </div>
        <div class="day column">
          <div class="day-banner">Wed</div>
          <div class="day-details">
            <div class="day-number">3</div>
          </div>
        </div>
        <div class="day column">
          <div class="day-banner">Thu</div>
          <div class="day-details">
            <div class="day-number">4</div>
          </div>
        </div>
        <div class="day column">
          <div class="day-banner">Fri</div>
          <div class="day-details">
            <div class="day-number">5</div>
            <div class="day-event" style="background-color: rgb(255, 153, 153)">
              <div>
                <span>Friday dinner/drinks</span> 
                <div><i class="fa fa-pencil-square edit-icon"></i> 
                  <i class="fa fa-trash-o delete-icon"></i>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="day column">
          <div class="day-banner">Sat</div>
          <div class="day-details">
            <div class="day-number">6</div>
          </div>
        </div>
        <div class="day column">
          <div class="day-banner">Sun</div>
          <div class="day-details">
            <div class="day-number">7</div>
          </div>
        </div>
      </div>
    </div>


    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.columns {
  display: grid;
  grid-template-columns: repeat(7, 1fr);
 
}

.day {
  border-right: 1px solid grey;
  background-color: #4A4A4A;
  color: white;
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