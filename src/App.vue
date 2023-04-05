<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <center><h1 style="font-size:large"> TREE I-DEA </h1>
 <img style="image-size:small;" src="./assets/logo(1).png">
  </center>
  <body>
    <form action="/action_page.php"></form> <label for="drink" >Design yang anda mau: </label>
  <select name="Design" id="Design">
    <option value="Design Benner">Design Benner</option>
    <option value="Design Id Card">Design Id Card</option>
    <option value="Design Invitation Wedding">Design Invitation Wedding</option>
    <option value="Design Invitation Wedding video">Design Invitation Wedding video</option>
    <option value="Design Invitation Wedding Website">Design Invitation Wedding Website</option>
  </select>
<p>
  Disini kami menawarkan kepada anda sekalia jasa untuk men design 
  dan menjamin kepuasan pembeli
</p>
</body>
<table>
  <tr>
    <th>NAMA</th>
    <th>CONTACT</th>
    <th>KAMPUS</th>
  </tr>
  <tr>
    <td>Dicky Syaputra</td>
    <td>08143879435</td>
    <td>UIN SUSKA RIAU</td>
  </tr>
  <tr>
    <td>Reyhan Zia Alfaiza</td>
    <td>087654389311</td>
    <td>UIN SUSKA RIAU</td>
  </tr>
</table> 
<input type="text" name="nama_user" value="masukkan nama anda"/>
<textarea name="Isi komentar" cols="40">
  Silahkan isi Komentar anda
</textarea>
</template>
<style>
h1 {color: rgb(250, 250, 250);}
form{margin-top: 5%;}
body {
    background-image: url("https://lumiere-a.akamaihd.net/v1/images/sa_pixar_virtualbg_coco_16x9_9ccd7110.jpeg");
  background-size: cover;}
  table, th, td {border:0.1px solid #ffffff; color: rgb(255, 255, 255);} 
  form,p {color: rgb(255, 255, 255);}
  label{color: rgb(255, 255, 255);}
</style>


