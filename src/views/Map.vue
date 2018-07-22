<template>
  <div class="map">
    <h1>Map</h1>

    <div id="tools">
        <input type="text" id="initialTime" value="18" class="small-input"></input>h.
        <button onclick="changeInitialTime()">Reinicia</button>
        <button onclick="start()">Start</button>
        <button onclick="pause()">Pause</button>
    </div>
    
  </div>
</template>

<style>
  .small-input{
    width:15px;
  }
</style>

