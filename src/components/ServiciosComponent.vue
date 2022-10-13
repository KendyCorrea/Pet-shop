<template>
    <div class="servicio">
      
        <h2>Entrenamiento <br>  <br>
 <img src="../assets/educa.jpeg" alt="">
 <Button>Saber más</Button>
        </h2>
             
  <h2>Higiene y peluquería. <br>  <br>
               <img src="../assets/Higi.jpeg" alt="">
                 <Button>Saber más</Button>
        </h2>

       <h2>
        Cuidado diario. <br>  <br>
           <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5tjCi6DPgq9suMlPAAGly32c9Ch-rs_hoew&usqp=CAU" alt="">
                 <Button>Saber más</Button>
       </h2>
  

       <h2>
         Venta de animales. <br>  <br>
           <img src="../assets/Ven.jpeg" alt="">
            <Button>Saber más</Button>
       </h2>
    
    <h2>
      Venta de alimentos. <br> <br>
        <img src="../assets/Alimento.jpg" alt="">
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
  name: 'ServiciosComponent',
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