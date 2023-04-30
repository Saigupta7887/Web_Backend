<template>

    <div>

        <center> <img :src= "book.photo" height="100" width="100"/> </center>
        <section id="companyname"><h4> Name: {{book.companyname}}</h4></section>
        <h4> Ranking : {{book.ranking}}</h4>
        <h4> Net worth in Millions : {{book.networth}}</h4>
        <h4> Website : {{book.website}}</h4>
        
        
        
    </div>

</template>

<script>




export default{
    name: 'BookItem',
    props:{
        book: Array
    }
}


</script>

<style scoped>

h2{
    text-align: center;
}

h1{
    text-align: center;
}
h4{
    text-align: center;
}
#companyname{
  background-color: rgb(64, 51, 180);
  color: black;
    padding: 1em;
    text-align: center;

}
#body{
  background-color: #e6ff00;
}
div{
    background-color: #ffdd9e;
    color: black;
    padding: 1em;
}

.red{
background-color: orangered !important;

}
.green{
    color: white;
}


</style>
