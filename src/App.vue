<script setup>

</script>





<template>
  <h1>BRAND CLOTHING</h1>
  <center><img src="https://o.remove.bg/downloads/833ea3f7-7e9e-42b9-af13-e7afbe2e4dc7/hydra-removebg-preview.png" alt="" style="width:500px;height:400px;"/></center>
  <h2><center>Login</center></h2>
  <form action="/action_page.php"><center>
    <label for="usname">Username:</label>
    <input type="text" id="usname" name="usname"><br><br>
    <label for="password">Password:</label>
    <input type="text" id="Password" name="Password"><br><br>
    <input type="submit" value="Submit"></center>

    <center><h3>Price list : </h3></center>
    <center><table style="width:30% ;height:30%;">

      <tr>
        <th>Menu</th>
        <th>Price</th>
      </tr>
      <tr>
        <td>oversize</td>
        <td>160k</td>
      </tr>
      <tr>
        <td>regular fit</td>
        <td>100k</td>
      </tr>
      <tr>
        <td> v neck</td>
        <td>100k</td>
      </tr>
      <tr>
        <td>kemeja </td>
        <td>250k</td>
      </tr>
      <tr>
        <td>slim fit</td>
        <td>100k</td>
      </tr>
    </table></center>
    <form action="/action_page.php" ><label for="drink" >Choose a drinks: </label>
      <select name="Type" id="Choose">
        <option value="Oversize">Oversize</option>
        <option value="regular fit">regular fit</option>
        <option value="v neck">v neck</option>
        <option value="kemeja">Kemeja</option>
        <option value="slim fit">slim fit</option>

      </select>
      <br><br>
      <input type="submit" value="Submit"></form>
  </form>
  <form action="/action_page.php">
    <p><label for="Cofee Shop">Kirim masukan atau saran dibawah ini:</label></p>
    <textarea id="Cofee Shop" name="Coffe Shop" rows="4" cols="50">Kritik Dan Saran</textarea>
    <br>
  </form>
  <p>lokasi Shop Hydra: Klik
    <a href="https://goo.gl/maps/CdH3RCoZZ7jzPZiK9">DISINI! </a>
  </p>

  <h4><center>Terima Kasih</center></h4>
  <h5><center>Sampai jumpa dan nantikan promo kami</center></h5>
  <h6>create by : Dicky syaputra </h6>
</template>

<style scoped>


</style>
<style>
h6 {margin-left: 85%;font-size: medium;  }
h5 {margin-top: -1%;font-size: medium}
form{margin-top: 5%;}
h3 {color: rgb(1, 8, 15);}
body {
  background-image: url("https://images.unsplash.com/photo-1501127122-f385ca6ddd9d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1935&q=80");
  background-size: cover;}
table, th, td {border:2px solid #433f3f; color: rgb(1, 8, 15);}
form,p {color: rgb(1, 8, 15);}
h2 {color: rgb(1, 8, 15);}
</style>