
<script>
export default{
    name:"AppHero"
}

</script>

<template>

<div class="jumbotron">
<h1>HELLO MONDO!</h1>

<P>Lorem ipsum dolor, sit amet consectetur adipisicing elit.
     Architecto,dolorum ullam mollitia ipsum quibusdam porro 
     est magni quisquam facilis fugiat!</P>

<hr>

<p class="p2">Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
    Dignissimos, voluptatem?</p>

  <button>Clicca</button>  
</div>

</template>

<style>
.jumbotron{
    border: 1px black solid;
    border-radius: 10px;
    padding: 20px;
    background-color: rgb(212, 206, 206);
}

button:active{
    background-color: lightpink;
    color: white;
}

.jumbotron .p2{
    font-weight: bolder;
}

</style>