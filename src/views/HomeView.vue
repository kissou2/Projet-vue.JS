<template>
  <div class="home">
   <div class="entete">
     <h3>LES HUMAINS DE NEW YORK</h3> <br> <br>
     <h1>Série</h1> <br> <br>
     <p class="p">Ces histoires se concentrent sur des populations<br>
     spécifiques, examinant leurs expériences et les défis<br>
      auxquels elles sont confrontées.</p> <br> <br>
   </div>
    <div class="serie1">
      <h3>LES HUMAINS DE NEW YORK </h3> <br> <br>
      <h1> Plaies <br> invisibles </h1> <br> <br>
      <input type="button" value="LIRE LA SERIE" class="boutton"
    </div>
    <div class="serie2">
      <h3>LES HUMAINS DE NEW YORK </h3> <br> <br>
      <h1>Cancer <br> pédiatrique</h1> <br> <br>
      <input type="button" value="LIRE LA SERIE" class="boutton"
    </div>
    <div class="serie3">
      <h3>LES HUMAINS DE NEW YORK </h3> <br> <br>
      <h1>Histoires de <br> détenus </h1> <br> <br>
      <input type="button" value="LIRE LA SERIE" class="boutton"
    </div>
    <div class="serie4">
      <h3>LES HUMAINS DE NEW YORK</h3> <br> <br>
      <h1>Américains <br> syriens</h1> <br> <br>
      <input type="button" value="LIRE LA SERIE" class="boutton"
    </div>
    <div class="serie5">
      <h3>LES HUMAINS DE NEW YORK</h3> <br> <br>
      <h1>Histoires de <br> réfugiers</h1> <br> <br>
      <input type="button" value="LIRE LA SERIE" class="boutton"
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style>
.entete{
  text-align: center;
  h3{
    font-size:20px;
    margin:0;
  }
  h1{
    font-size:150px;
    font-family: GT Sectra Display Light;
    margin:0;
    padding:0

  }
  .p{
    font-size:50px;
    font-family:GT Sectra Display;
    margin:0;
  }
}
.serie1{
  background-image: url(../assets/1.jpg);
  height: 1000px;
   background-repeat: no-repeat;
  background-size:  contain; 
  position: relative;
  padding-left: 900px;
  justifi-content: center;
   h1{
      color:clear chocolate;
    }

  }
   h1{ 
    font-size:115px;
  font-family: GT Sectra Display Light;
  }
  h3{
    font-size:15px;
  font-family: Akzidenz-Grotesk BQ;
  margin:0;
  padding:70px;


}
.boutton{
   padding: 15px;
   padding-right:50px;
    background: none;
    border-radius: 0px;
    justifi-content:center;
    padding-left:50px
   
}
.serie2{
  background-image: url(../assets/2.jpg);
  height: 1000px;
   background-repeat: no-repeat;
  background-size:  contain; 
  position: relative;
  padding-right: 900px;
  justifi-content: center;
  h1{
    color:red;
  }
  
  
 
}
.serie3{
  background-image: url(../assets/3.jpg);
   height: 1000px;
   background-repeat: no-repeat;
  background-size:  contain; 
  position: relative;
  padding-left: 900px;
  justifi-content: center;
   h1{
    color: green;
  }
   
}
.serie4{
 background-image: url(../assets/4.jpg);
   height: 800px;
   background-repeat: no-repeat;
  background-size:  contain; 
  position: relative;
  padding-right: 900px;
  justifi-content: center;
  h1{
    color: yellow;
  }
}
.serie5{
  background-image: url(../assets/5.jpg);
   height: 1000px;
   background-repeat: no-repeat;
  background-size:  contain; 
  position: relative;
  padding-left: 900px;
  justifi-content: center;
  magin-rigth:0;
   h1{
    color: black;
  }

}
</style>
  