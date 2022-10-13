<template>
    <div class="servicio">
      
        <h2>Perros <br>  <br>
 <img src="../assets/Perro.jpg" alt="">
 <Button>Saber más</Button>
        </h2>
             
  <h2>Gatos <br>  <br>
               <img src="../assets/Gato.jpg" alt="">
                 <Button>Saber más</Button>
        </h2>

       <h2>
        Hámsters <br>  <br>
           <img src="../assets/Hámster.jpg" alt="">
                 <Button>Saber más</Button>
       </h2>
  

       <h2>
         Pájaros <br>  <br>
           <img src="../assets/Pájaro.jpg" alt="">
            <Button>Saber más</Button>
       </h2>
    
    <h2>
      Peces <br> <br>
        <img src="../assets/Peces.jpg" alt="">
         <Button>Saber más</Button> 
    </h2>
     <h2>
      Venta de accesorios.  <br> <br>
        <img src="../assets/Acces.jpeg" alt="">
         <Button>Saber más</Button> 
    </h2>
    </div>
</template>


<script lang="ts">
export default ({
  name: 'TipoMascotaComponent',
});
</script>

<style scoped>
.servicio{
    display: grid;
    gap: 3rem;
    grid-auto-rows: 27rem;
    grid-template-columns: repeat(auto-fit,minmax(15rem,1fr));
    color: black;
}
h1{
  color:black;
 text-decoration: underline black;
}
img{
  height: 230px;
    width: 290px;
}
Button{
display: inline-block;
    font-size: 24px;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    outline: none;
    color: #fff;
    background-color: #4caf50;
    border: none;
    border-radius: 15px;
    box-shadow: 0 9px #999;
}
</style>