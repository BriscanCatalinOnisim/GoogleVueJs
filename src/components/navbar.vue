<template>
  <div class="headerRight">
    <router-link class="menu-item _menu _link" to="/">Gmail</router-link>
    <router-link class="menu-item _menu _link" to="/">Images</router-link>
    <div class="menu-item _menu">
      <a href="#">
        <svg class="menu" focusable="false" viewBox="0 0 24 24">
          <path
            d="M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z"
          ></path>
        </svg>
      </a>
    </div>
    <div class="menu-item1">
      <a href="#"><img src="../assets/me.png" class="myphoto"/></a>
    </div>
  </div>
</template>
<style scoped>

.headerRight {
  display: flex;
  font-size: 13px;
  color: rgba(0, 0, 0, 0.87);
  position: fixed;
  right: 0; /* for it to be responsive */
  top: 15px;
  z-index: 2;
}
.menu-item {
  padding-top: 7px;
  padding: 5px;
}

.menu-item1 {
  padding-top: 7px;
  padding: 5px;
}

.menu-item._menu {
  padding-top: 13px;
}
.menu-item._menu._link {
  padding-top: 16px;
}

.menu:hover {
  box-shadow: 1px 5px 10px #949494;
  background-color: rgba(60, 64, 67, 0.08);
  border-radius: 50%;
}

a:visited {
  color: rgba(0, 0, 0, 0.87);
}
a {
  color: rgba(0, 0, 0, 0.87);
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}

.menu {
  height: 24px;
  width: 24px;
  fill: rgb(95, 99, 104);
}

.myphoto {
  border-radius: 50%;
  padding: 5px;
  width: 30px;
}

.myphoto:hover {
  box-shadow: 1px 5px 10px #949494;
  background-color: rgba(60, 64, 67, 0.08);
  border-radius: 50%;
}

</style>