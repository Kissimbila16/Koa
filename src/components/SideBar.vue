<template>
    <section>
        <div>
             <h4 style="text-align:center;margin-top:60px;font-weight:600;font-family:arial;">
                Menu Principal
             </h4>
             
            <ol>
<li><a href="home">Home</a></li>
<li><a href="about">About</a></li>
<li><a href="contact">Contact</a></li>
<li><a href="information">Information</a></li>
<li><a href="https://www.google.com/koa.js" target="_blank">Koa.js</a></li>
<li><a href="exit">Exit</a></li>
            </ol>
        </div>
    </section>
</template>

<script>
export default {
    name:"SidebarLayout",
    components() {
        
    },
  
}
</script>
<style scoped>

li{

    margin-top:20px;
}
a{
     text-decoration: none;
     color:white;
     font-size:14px;
     font-weight: 500;

}     

a:hover{
      font-weight: 700;
}
 ol{
     list-style: none;
      display: grid;
      color:black;
      font-family: arial;
      font-weight: 600;
      text-align: left;
 }

section{
     height:88vh;
      width:300px;
       background: black;
       color:white;
}
</style>