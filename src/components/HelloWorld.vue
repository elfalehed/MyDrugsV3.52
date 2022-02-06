<template>
  <div class="hello">
      <div class="sidenav">
        <a id="ex">HOME</a>
         <a href="#">DATABASE</a>
          <a href="#">ANALYTICS </a>
          <a href="#">REPORT </a>
          <a href="#">RATINGS </a>
          <a href="#">TESTINGS</a>
</div>
<div class="vl"></div>
<div class="intro">
<p id="ps1">MY DRUGS V3.52 | <b>WELCOME, M1000</b></p><p id="prd">PRODUCTS : </p><br>
</div> <br> <br>
<div class="list-shop">
  <table>
    <tr>
      <td>
  <img src="@/assets/mdma.png" height="60px;" style="border-radius:20px;"> </td> <td> <p class="pilltag">&nbsp; PILL1 </p> </td> <td class="pilltag">&nbsp;| &nbsp;  0 </td> </tr> <!-- <p style="color: white;" id="mdma1">MDMA1</p> --><br>
  <tr> <td> <img src="@/assets/mdma1.jpg" height="60px" style="border-radius:20px;"> </td> <td> <p class="pilltag">&nbsp; PILL2 </p> </td> <td class="pilltag"> &nbsp; | &nbsp; 0 </td>  </tr> <br>
  <tr> <td>  <img src="@/assets/mdma2.jpg" height="60px" style="border-radius:20px;"></td> <td> <p class="pilltag">&nbsp; PILL3 </p> </td> <td class="pilltag">&nbsp;|  &nbsp; 0 </td> </tr> <br>
   <tr> <td> <img src="@/assets/mdma3.jpg" height="60px" style="border-radius:20px;"> </td> <td> <p class="pilltag">&nbsp;  PILL3 </p> </td> <td class="pilltag">&nbsp;| &nbsp; 0 </td></tr><br>
  </table>
  </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
 color:white;
 border: 1px solid #313552;
 border-radius: 8px;
 width: 200px;
}
body{
    background-color: #1A1A40;
}
#mdma1{
  font-size: 30px;
}
#logout{
  text-align: left;
  font-size: 25px;
}
.sidenav {
  height: 100%; /* Full-height: remove this if you want "auto" height */
  width: 230px; /* Set the width of the sidebar */
  position: fixed; /* Fixed Sidebar (stay in place on scroll) */
  z-index: 1; /* Stay on top */
  top: 0; /* Stay at the top */
  left: 0;
  overflow-x: hidden; /* Disable horizontal scroll */
  padding-top: 20px;
}
.pilltag{
  color: white;
  font-size: 25px;
}
/* The navigation menu links */
.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  display: block;
}
#ex{
  background: linear-gradient(45deg,#FFAB76, #FF6363);
}
/* When you mouse over the navigation links, change their color */

/* Style page content */
.main {
  margin-left: 160px; /* Same as the width of the sidebar */
  padding: 0px 10px;
}
.navbar {
  overflow: hidden;
  position: fixed; /* Set the navbar to fixed position */
  top: 0; /* Position the navbar at the top of the page */
  width: 100%; /* Full width */
}
#logout{
    text-align:left;
}
#prd{
  font-size:35px;
  color: white;
  position: fixed;
  left:350px;
  top: 8%;
}
#ps1{
  position:fixed;
  top:-5%;
  left:350px;
}
/* On smaller screens, where height is less than 450px, change the style of the sidebar (less padding and a smaller font size) */
@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
.list-shop{
  position: fixed;
  left:350px;
}
.vl {
  border-left: 1px solid #313552;
  height: 100%;
  position: absolute;
  left: 15%;
  top: 0;
}
.intro{
  color: white;
  font-size: 50px;
  top: 0;
}
</style>
