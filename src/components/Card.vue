<template>
    <div>
       <div  id="cards" class="card" style="width: 18rem;">
        <img src="../assets/logo.png" class="card-img-top" alt="...">
        <div class="card-body">
            <h5 class="card-title">{{nombre}}</h5>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        </div>
            </div>
</template>

<script>
    
      export default {
        name: 'Card',
        props: {
                 nombre: String
                 
                }
       }
    
</script>

<style  scoped>
#cards{
    margin-top:20px;
}
img{
    padding: 20px;
}
  

</style>