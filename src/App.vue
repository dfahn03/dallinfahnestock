<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
  #app {
    font-family: 'Monda', sans-serif;
    color: white;
    text-align: center;
    user-select: none;
    padding: 0px 0px;
    margin: 0px 0px;
  }

  html,
  body,
  div {
    margin: 0 !important;
    padding: 0 !important;
    width: 100%;
  }

  html,
  body {
    overflow-x: hidden;
  }
</style>