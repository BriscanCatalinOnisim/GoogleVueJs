<template>
  <div class="footerRo">
    <a href="#" class="textLink">Romania </a>
  </div>
</template>

<style>
.footerRo {
  display: flex;
  position: relative;
  margin-top: 240px;
  padding: 2px 10px;
  background-color: #f2f2f2;
  border-bottom: 1px solid #dadce0;
  color: rgba(0, 0, 0, 0.54);
}

@media only screen and (max-width:650px) {
   .footerRo {
        display: block;
        height:50px;
        flex-direction: column;
        text-align: center;
        width: 100%;
    }
}

</style>