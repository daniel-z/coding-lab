<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>
    </div> -->
    <div class="hero">
      <div class="header-wrapper">
        <header>
          <h1>Code Experiments</h1>
          <h2>
            <a target="_blank" href="https://www.danielzamorano.pro">
              By Daniel Zamorano
            </a>
          </h2>
        </header>
      </div>
    </div>
    <router-view />
    <footer>
      <p class="about">
        <a target="_blank" href="https://www.danielzamorano.pro">
          Daniel Zamorano / 2019
        </a>
      </p>
    </footer>
  </div>
</template>

<style lang="scss" src="./App.scss"></style>
