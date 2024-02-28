
<script>
export default{
    name:"AppHero",

    data(){
        return{
            nome:"ALAN",
            conto:0
        }
    },

    methods:{
     countIncrease(){
        this.conto++
     }
    }
}

</script>

<template>

<div class="jumbotron">
<h1>HELLO {{ nome }}</h1>

<P>Lorem ipsum dolor, sit amet consectetur adipisicing elit.
     Architecto,dolorum ullam mollitia ipsum quibusdam porro 
     est magni quisquam facilis fugiat!</P>

<hr>

<p class="p2">Lorem ipsum dolor sit amet consectetur, adipisicing elit. 
    Dignissimos, voluptatem?</p>

  <button @click="countIncrease()">Count ++</button> 
  <span>{{ conto }}</span> 
</div>

</template>

<style>
.jumbotron{
    border: 1px black solid;
    border-radius: 10px;
    padding: 20px;
    background-color: rgb(212, 206, 206);
}

span{
    margin-left: 20px;
    padding: 5px;
    background-color: black;
    color:gold;

}
button:active{
    background-color: lightpink;
    color: white;
}

.jumbotron .p2{
    font-weight: bolder;
}

</style>