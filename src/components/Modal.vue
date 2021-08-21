<template>

  <div class="backdrop">
      <h1>{{title}}</h1>
  <div class="modal">
    <p>Modal Contetnt</p>
    
  </div>
  
</div>

</template>

<script>
export default {
    data()
    {
        return{
            title:'this is my first vue app'
        }
    },

}
</script>

<style>
.modal{

    width:400px  ;
    padding:20px ;
    margin:100px auto ;
    background: white;
    border-radius: 10px;
}
.backdrop{
top: 0px;
position: fixed;
background: rgba(0,0,0,0.5);
width: 100%;
height: 100%;

}

</style>