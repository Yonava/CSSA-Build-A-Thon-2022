<template>
  <div id="app">
    <header>
      <a 
        class="sign-up"
        href="https://forms.gle/yP9vPjvE54VciRQe8"
        target="_blank"
      >
        <button>
          Team Sign-Up Form
        </button>
      </a>
    </header>
    <div style="width: 100%; height: 25px;"></div>
    <div style="text-align: center; padding: 20px; padding-buttom: 0px">
      <h1>Welcome to Software Build-A-Thon</h1>
      <h3 class="title-sub-heading">CSSAs Flagship Fall 2022 Event</h3>
    </div>
    <div class="center">
      <div style="width: 90%; height: 1px; background-color: white;"></div>
    </div>
    <div class="info">
      <h2 class="info-heading">Why Participate?</h2>
      <ul>
        <li>Create a project for your resume</li>
        <li>Get feedback from judges with industry experience</li>
        <li>Receive a cssa build-a-thon t-shirt</li>
        <li>Get a $10 amazon gift card for completed software, even if you don't win</li>
      </ul>
      <h2 class="info-heading">The Prize Pool</h2>
      <ul>
        <li>1st Place Team: <b>$500.00*</b></li>
        <li>2nd Place Team: <b>$350.00</b></li>
        <li>3rd Place Team: <b>$150.00</b></li>
      </ul>
      <p>* The CSSA is seeking conference approval from SGA. Currently 
        our conference budget has OSI approval, 
        final approval will be given on or shortly after Nov 15th. If given 
        final approval from SGA, 
        the winning team will receive an offer to be sent, 
        with full expenses paid, to one of texas largest tech conferences
        <a
          href="https://that.us/events/tx/2023/" 
          target="_blank" 
          class="conf-link"
        >THAT Con</a>
        in exchange for the cash prize.
      </p>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
.title-sub-heading {
  color: white;
  margin: 0%;
  margin-top: 5px;
  font-weight: normal;
}

body {
  background-color: rgb(26, 26, 26);
  padding: 0%;
  margin: 0%;
}

div.center {
  display: flex;
  justify-content: center;
  align-items: center;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}

h1 {
  color: white;
  margin: 0%;
}

header {
  display: flex;
  justify-content: left;
  align-items: center;
  width: 100vw;
  height: 75px;
  background-color: rgba(255, 255, 255, 0.2);
  top: 0;
  position: fixed;
}

button {
  padding: 10px;
  border: 2px solid black;
  border-radius: 5px;
  background-color: white;
  cursor: pointer;
  font-size: 2ch;
  color: black;
  font-weight: bold;
}

div.info {
  /* margin-top: 5px; */
  padding: 20px;
  display: flex;
  justify-content: left;
  align-content: left;
  align-items: left;
  color: white;
  flex-direction: column;
}

h2.info-heading {
  margin: 0%;
}

a.sign-up {
  margin-left: 15px;
  text-decoration: none;
}

a.conf-link {
  color: white;
}
</style>
