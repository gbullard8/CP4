<template>
<div id="app">
  <div class="header">
    <div class="title">
      <h1>Smith's Classic Cars</h1>
    </div>
  </div>
      <router-link to="/">
      <div class="logo">
        <img src="/logo.jpg">
      </div>
    </router-link>

  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/admin">Edit Items</router-link>
    <a href='https://github.com/gbullard8/CP4.git'> github</a>
  </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
  text-align: center;
  
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #e3e3e3;
  color: #000;
  text-align: center;
}

.title {
  margin-top: 5px;
  margin-left: auto;
  margin-right: auto;
}

.title h1 {
  font-size: 30px;

}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 50px;
  padding: 20px 100px 0px 100px;
  background: #e3e3e3;
  font-size: 12px;
}

.footer a {
  color: #000;
  margin-right: 20px;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
