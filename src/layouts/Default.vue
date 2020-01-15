<template>
  <div class="layout">
    <header class="header">
        <h4>Paula Diniz</h4>
      <nav>
        <g-link class="nav__link active" to="/">Home</g-link>
        <g-link class="nav__link" to="/about/">Sobre</g-link>
      </nav>
    </header>
    <slot/>
  </div>
</template>

<script>
export default {
  
}
</script>
<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
  font-family: Karla, "Arial";
  margin:0;
  padding:0;
  line-height: 1.5;
}

.header {
  display: flex;
  height: 70px;
  background-color:#333366;
  border-top: 10px solid #eb4d55;
  justify-content: center;
  align-items: center;
  box-shadow: 0 10px 12px 0 rgba(22, 21, 32, 0.10);
  margin-bottom: 20px;
}

h4 {
  color: #fff
}

.nav__link {
  margin-left: 30px;
  color: #fff;
  text-decoration: none;
  text-transform: uppercase
}
.nav__link:hover {
  border-bottom: 5px solid #FFF;
  transition: all 0.5s ease;
  padding: 5px 0
}
</style>
