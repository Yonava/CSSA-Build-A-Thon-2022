<template>
  <div id="app">
    <header>
      <div style="margin: 6px 0px 0px 10px">
        <p class="header-subtitle">Competition Over</p>
        <h1 class="header-title">Thanks For Playing!</h1>
      </div>
      <!-- <a 
        class="sign-up"
        href="https://forms.gle/yP9vPjvE54VciRQe8"
        target="_blank"
      >
        <button>
          Sign-Up Form
        </button>
      </a> -->
      <!-- <p style="color: white; margin-left: 10px">Sign-Ups Close Nov 13th</p> -->
    </header>
    <div style="text-align: center; padding: 20px; padding-buttom: 0px">
      <h1>Welcome to Software Build-A-Thon</h1>
      <h3 class="title-sub-heading">CSSA's Flagship Fall 2022 Event</h3>
    </div>
    <div class="center">
      <div style="width: 90%; height: 1px; background-color: white;"></div>
    </div>
    <div class="info">   
      <h2 class="info-heading">Closing Ceremony Info</h2> 
      <p>
        Monday, SETA 118A/B at 6:30p. Teams present, winners announced. Everyone welcome so bring friends! food and drink provided.
      </p>
      <h2 class="info-heading">Why Participate?</h2>
      <ul>
        <li>Create a project for your resume</li>
        <li>Get feedback from judges with industry experience</li>
        <li>Receive a CSSA t-shirt</li>
        <li>Get a $10 Amazon gift card for completed software, even if you don't win</li>
        <li>Enjoy dinner provided by CSSA and SETA at the opening and closing ceremony</li>
      </ul>
      <h2 class="info-heading">The Prize Pool</h2>
      <ul>
        <li>1st Place Team: <b>Trip to Texas or $500.00*</b></li>
        <li>2nd Place Team: <b>$350.00</b></li>
        <li>3rd Place Team: <b>$150.00</b></li>
      </ul>
      <p>
        * The CSSA offers to fly the winning team of the Software Build-A-Thon out to
        Austin, Texas for
        <a
          href="https://that.us/events/tx/2023/schedule" 
          target="_blank" 
          class="conf-link"
        >THAT Con</a>
        - all expenses paid. If winning team decides to take the $500, the second place
        winners will receive an opportunity to accept the conference trip.
      </p>
      <h2 class="info-heading">What Am I Signing Up For?</h2>
      <p>
        The CSSA Software Build-A-Thon is a software building competition.
        Teams of 2-3 will compete over Friday (18th) night, Saturday (19th), and Sunday (20th)
        to build a piece of software based on a general theme that will be announced at
        the opening ceremony on the 18th @ 6:30p SETA 118A/B. On Monday (21st) is our closing
        ceremony, which will take place in SETA 118A/B at 6:30p as well. Teams are going to present what they built and the winners will be announced!
      </p>
      <h2 class="info-heading">How Does My Team Win?</h2>
      <p>
        Our judges will be evaluating every teams project
        to determine the winner based on a set of criteria including
        how the code is organized (software craftsmanship), how creative is your team's
        idea and the approach your team uses to turn your idea into a reality.
        Factors like design pattern implementation may be observed as well.
      </p>
      <h2 class="info-heading">FAQs</h2>
      <p><b>Do I Need to Know How to Code?</b></p>
      <p class="faq-answers">
        Not necessarily, however, you should find a teammate who does know how to code.
        Software development is multi-faceted. If you are a graphic designer
        who has knowledge in Figma or Adobe products but are scared off by
        the prospect of writing code, find someone who programs and build something
        awesome together!
      </p>
      <p><b>What Language or Framework are Teams Required to Use?</b></p>
      <p class="faq-answers">
        We don't discriminate! If you are a game dev with a lot of Unity or
        Unreal experience, build a game. If you are a front-end dev, build an
        app or website. Back-end? make a console app or API. There will be
        infinite ways to engage our theme. We are judging your approach to
        building software, not the flashiness. We understand that building a
        C++ app that renders ASCII graphics from scratch will be much harder to pull off than
        using tools built into advanced game engines.
      </p>
      <p><b>Can I Sign-Up Without A Team?</b></p>
      <p class="faq-answers">
        Sure. Just write "TBD" as your team name and we will match you
        with others at the opening ceremony!
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

p.header-subtitle {
  font-weight: 500;
  color: white;
  margin: 0%;
}

h1.header-title {
  font-weight: 900;  
  transform: translateY(-3px);
}

header {
  display: flex;
  justify-content: left;
  text-align: left;
  width: 100vw;
  height: 70px;
  background-color: rgb(49, 122, 50);
  top: 0;
  position: fixed;
  z-index: 2;
  flex-direction: column;
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
  position: sticky;
  top: 70px;
  background-color: rgb(26, 26, 26);
}

p.faq-answers {
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
