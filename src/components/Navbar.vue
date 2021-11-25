<template>
    <div>
      
         <ul class="nav">
            <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Inicio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">{{titulo}}</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contacto</a>
            </li>
            <li class="nav-item">
                <a class="nav-link ">Galeria</a>
            </li>
        </ul>
     </div>   
    
</template>

<script>
    export default {
        name: 'Navbar',
        props: {
                 titulo: String,
                 
                }
       }
</script>

<style  scoped>

</style>