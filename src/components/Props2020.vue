<template>
  <div id="2020PropsMain">
    <img
      alt="Promo header"
      src="../assets/moretrains.png"
      height="auto"
      width="80%"
    />
    <h1>
      <a href="https://austinanthem.org">Austin Anthem</a> and <a href="https://losverdesatx.org">Los Verdes</a> support Austin's Proposition A and
      Proposition B.
    </h1>
    <br>
        <table id="propsigns">
      <tr>
        <td>
          <a href="https://www.transitnowatx.com/">
            <img
              alt="Prop A sign"
              src="../assets/prop-a-yard-sign.jpg"
              height="auto"
              width="100%"
          /></a>
        </td>
        <td>
          <a href="https://www.safemobilityforall.org/">
            <img
              alt="Prop B sign"
              src="../assets/prop-b-yard-sign.jpg"
              height="auto"
              width="100%"
            />
          </a>
        </td>
      </tr>
    </table>
    <table id="PropInfo">
      <tr class="propseparator">
        <td class="propseparatorleft"><h2>What is Proposition A?</h2></td>
        <td class="propseparatorright">
          Proposition A is the $7.2b plan to add three new rail lines and an
          expanded, all-electric bus fleet with more rapid lines across the
          city. Included in this plan is a new Red Line station directly on the stadium grounds at McKalla Place, with all three new rail lines connecting directly to the Red Line for matchday travel ease.<br />
          <b
            >We support this proposition because we believe it's time for a bold
            investment in the future of Austin's transit system.</b
          >
          This proposition will help all Austinites get to work in a more
          efficient, climate-friendly manner during the week, and get us all to
          McKalla Place without having to fight traffic on matchdays.
          <br />
          Learn more about Project Connect on the
          <a href="https://www.capmetro.org/project-connect"
            >Capital Metro website</a
          >, and more about the benefits
          <a href="https://www.transitnowatx.com/"
            >at the Transit Now! website.</a
          >
        </td>
      </tr>
      <tr>
        <td class="propseparatorleft"><h2>What is Proposition B?</h2></td>
        <td class="propseparatorright">
          Proposition B will build new trails, sidewalks, and safer streets
          across the city. Among the highlights of the plan include $80m for
          sidewalks, $80m for urban trails, $40m for bikeways, and a new
          pedestrian bridge near Longhorn Dam on the east reaches of Lady Bird
          Lake.
          <br /><b
            >We support this proposition because now more than ever, we believe
            that having an active transport network for our entire city makes us
            a safer, healther Austin.</b
          > This is an investment for our generation and the next.
          <br />
          Learn more about Proposition B at the
          <a href="https://www.safemobilityforall.org/"
            >Safe Mobility For All website.</a
          >
        </td>
      </tr>
    </table>
  </div>
</template>
<style scoped>
html  a:link,
a:visited{
  color: #ffffff;
}
#PropInfo {
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  display: relative;
  justify-content: center;
  border-collapse: collapse;
  width: 80%;
}
.propseparatorright {
  border-top: 5px solid black;
  padding-right: 0;
  text-align: left;
  padding-left: 25px;
  padding-bottom: 20px;
  padding-top: 10px;
}
.propseparatorleft {
  border-top: 5px solid black;
  padding-right: 0;
  text-align: center;
  padding-bottom: 20px;
  padding-top: 10px;
}
#propsigns {
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  display: flex;
  justify-content: center;
  max-width: 80%;
}
@media only screen and (max-width: 760px),
  (min-device-width: 768px) and (max-device-width: 1024px) {
.propseparatorright {
  padding-left: 0px;
}
}
</style>