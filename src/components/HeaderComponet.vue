<script setup>
</script>

<template>
  <div class="header-navbar">
    <div class="left-navbar">
      <img alt="Monkey Logo" class="logo" src="@/assets/monkey_logo.jpg" width="100" height="100" />
      <p>MONKY FM</p>
    </div>
    <div class="right-navbar">
      <button class="login">LOGIN</button>
    </div>
  </div>
</template>

<style scoped>
.header-navbar {
  margin: 0px;
  padding: 0px;
  background-color: #0f1620;
}

.left-navbar{
  float: left;
}
.left-navbar p{
  float: right;
  font-size: 50px;
  color: #ffffff;
  margin-top: 5%;
  font-family: Monospace;
}

.right-navbar {
  float: right;
}

.login {
  margin-top: 22%;
  margin-right: 30px;
  background: #2a2a57;
  border-radius: 999px;
  box-shadow: #19191f 0 10px 20px -10px;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  font-family:  sans-serif;
  font-size: 16px;
  font-weight: 700;
  line-height: 24px;
  opacity: 1;
  outline: 0 solid transparent;
  padding: 8px 18px;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  width: fit-content;
  word-break: break-word;
  border: 0;
}
.login:disabled {
  pointer-events: none;
}

.login:hover {
  box-shadow: rgba(0, 0, 0, 0.25) 0 8px 15px;
  transform: translateY(-2px);
  opacity: .75;
}

.login:active {
  box-shadow: none;
  transform: translateY(0);
}
</style>
