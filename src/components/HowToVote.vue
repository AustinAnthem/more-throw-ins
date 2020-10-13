<template>
<div>
    <table id="voterinfotable">
      <tr>
        <h1>Voter Information</h1>
        City of Austin residents have their elections overseen by Travis County or Williamson County. If you live
        outside the City of Austin, you won't be able to vote on these
        propositions - but it's still hugely important to vote the entire
        ballot, and encourage your Austin friends to consider these propositions.
      </tr>
    </table>
    <table id="countytable">
      <tr>
        <table>
            <th>County</th>
            <th>Elections Info</th>
          <tr>
            <td class="countyname">Travis County</td>
            <td class="countyurl">
              <a href="https://votetravis.com/vexpress/display.do"
                >VoteTravis</a
              >
            </td>
          </tr>
          <tr>
            <td class="countyname">Williamson County</td>
            <td class="countyurl">
              <a href="https://www.wilco.org/Departments/Elections"
                >Williamson County Elections</a
              >
            </td>
          </tr>
          <tr>
            <td class="countyname">Hays County</td>
            <td class="countyurl">
              <a href="https://hayscountytx.com/departments/elections/"
                >Hays County Elections</a
              >
            </td>
          </tr>
          <tr>
            <td class="countyname">Blanco County</td>
            <td class="countyurl">
              <a href="http://www.co.blanco.tx.us/page/blanco.Elections"
                >Blanco County Elections</a
              >
            </td>
          </tr>
          <tr>
            <td class="countyname">Bastrop County</td>
            <td class="countyurl"><a href="https://www.bastropvotes.org/">BastropVotes</a></td>
          </tr>
          <th>Other Region</th>
          <th>Voting Information</th>
          <tr>
              <td class="countyname">State of Texas</td>
              <td class="countyurl"><a href="https://www.votetexas.gov/">VoteTexas</a></td>
          </tr>
          <tr>
              <td class="countyname">United States</td>
              <td class="countyurl"><a href="https://vote411.org">Vote411</a></td>
          </tr>
        </table>
      </tr>
    </table>
    </div>
</template>
<style scoped>
#voterinfotable {
  background-color: black;
  text-align: center;
  margin-left:auto;
  margin-right:auto;
  display: flex;
  justify-content: center;
  width: 80%;

}
html a:link, a:visited {
  color: #000000;
}
h1 {
  color: #00b140;
}
#countytable {
  background-color: black;
  text-align: center;
  margin-left:auto;
  margin-right:auto;
  display: flex;
  justify-content: center;
  width: 80%;
}
.countyname{
  text-align: center;
  background-color: #00b140;
  font-weight: 800;
  font-size: 20px
}
.countyurl{
  text-align: center;
  background-color: #00b140;
  font-weight: 800;
  font-size: 20px;
}
</style>