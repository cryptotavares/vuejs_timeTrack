<template>
  <div id="wrapper">
    <nav class="navbar navbar-dark bg-inverse">
      <div class="container">
        <a class="navbar-brand" href="#">
          <i class="glyphicon glyphicon-time"></i>
          Time tracker
        </a>
        <ul class="nav navbar-nav">
          <li><a v-link="'/home'">Home</a></li>
          <li><a v-link="'/time-entries'">Time Entries</a></li>
        </ul>
      </div>
    </nav>
    <div class="container">
      <div class="col-sm-3">
        
      </div>
      <div class="col-sm-9">
        <router-view></router-view>
      </div>
      
    </div>
  </div>
</template>
