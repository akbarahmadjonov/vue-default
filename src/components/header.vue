<template>
  <div class="nav">
    <div>
      <h1>Vue World</h1>
      <button class="btn btn-primary mt-5">Click</button>
    </div>

    <div class="linkes">
      <a href="#">Home</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
      <a href="#">Portfolio</a>
      <a href="#">Search</a>
    </div>
  </div>
</template>

<style>
.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-left: 40px;
  margin-right: 40px;
  font-family: Calibri;
}

a {
  margin-left: 20px;
  margin-right: 20px;
  text-decoration: none;
  color: #2c3a47;
}

h1 {
  font-size: 35px;
  animation: leftTop 3s infinite;
}

@keyframes leftTop {
  0% {
    color: black;
  }

  25% {
    color: #2c3a47;
  }

  50% {
    color: tomato;
  }

  75% {
    color: darkgray;
  }

  100% {
    color: #63ace5;
  }
}
</style>
