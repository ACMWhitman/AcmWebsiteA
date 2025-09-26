<script setup>
</script>

<template>
  <div class="landing">
    <div class="centerfold">
      <div class="images">
        <a href="https://www.whitman.edu/" target="_blank"><img src="/blues.png"></img></a>
        <a href="https://www.acm.org/"  target="_blank"><img src="/acm.png"></img></a>
      </div>
      <div class="h1">Whitman ACM</div>
      <div>Association for Computing Machinery, Whitman College Chapter</div>
      <br></br>
      <div class="button">Register Here</div>
    </div>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');
.h1{
  font-size:40px;
}
.landing{
  height:70vh;
  display:flex;
  flex-flow:row;
  align-items: center;
  justify-content: center;

}

.centerfold {
  display: flex;
  flex-flow: column nowrap;
  align-items: center;
  gap: 10px;
  color:var(--darkblue)
}
html{
  background-color:var(--grey);
}
.images img {
  height:100px;
}
.button{
  padding:10px;
  border-radius:10px;
  border:solid 3px var(--grey);
  outline:solid 3px var(--yellow);
  background-color:var(--blue);
  color:var(--yellow);

  cursor:pointer;
  font-size:20px;

}
.button:hover{
  text-decoration: solid underline;
}

</style>