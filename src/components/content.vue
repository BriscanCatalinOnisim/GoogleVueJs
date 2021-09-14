<template>
    <main class="main">
      <img src="../assets/google.png" class="logo" />

      <div class="search">
        <img src="../assets/search.svg" class="icon-search"/>
        <input type="search" class="search-input" />
        <img src="../assets/mic.svg" class="icon-mic"/>
      </div>

      <div class="main-buttons">
        <button class="buttons">Google Search</button>
        <button class="buttons">I'm Feeling Lucky</button>
      </div>

      <div class="languages">
        <p>Google offeres in:</p>

        <div class="language-type">
           <a class="lang" href="">Romana</a>
           <a class="lang" href="">magyar</a>
           <a class="lang" href="">Deutsch</a>
        </div>
      </div>
    </main>
</template>



<style scoped>

.languages {
  display: flex;
  justify-content: center;
  align-items: center;
  color: #3c4043;
}
.language-type {
  padding: 5px;
}

.lang {
  color: #1a0dab;
}

.buttons {
  background-color: #f8f9fa;
  border: 1px solid #f8f9fa;
  border-radius: 4px;
  color: #3c4043;
  font-family: arial, sans-serif;
  font-size: 14px;
  margin: 11px 4px;
  padding: 0 16px;
  line-height: 27px;
  height: 36px;
  min-width: 54px;
  text-align: center;
  cursor: pointer;
  user-select: none;
}

.buttons:hover {
  border-radius: 4px;
  margin: 11px 4px;
  padding: 0 16px;
  line-height: 27px;
  height: 36px;
  min-width: 54px;
  text-align: center;
  cursor: pointer;
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.1);
  border: 1px solid #dadce0;
  color: #202124;
}

.search {
    background: #fff;
    display: flex;
    border: 1px solid #dfe1e5;
    box-shadow: none;
    border-radius: 24px;
    z-index: 3;
    height: 44px;
    margin: 0 auto;
    width: 482px;
    width: auto;
    max-width: 584px;
}

.search:hover {
  box-shadow: 0 1px 6px rgb(32 33 36 / 28%);
  border-color: rgba(233, 225, 229, 0);
}

.search-input {
  flex: 1;
  border: none;
  outline: none;
  color: rgba(0, 0, 0, 0.87);
  font-size: 1.6rem;
  padding: 0 1.3rem;
}

.icon-search {
  width: 2rem;
  margin-left: 14px;
}

.icon-mic {
  margin-right: 14px;
  height: 90%;
  cursor: pointer;
}


/* Remove the headerRight for smaller screens */
@media all and (max-width: 1024px) {
  .__search.withOutButtons {
    max-width: 65%;
  }
}
</style>