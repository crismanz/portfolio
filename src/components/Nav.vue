<template>
  <div id="nav">  
    <nav>
      <div class="navbar">
        <a class="brand" href="#hello">Cristina Manzoni</a>
        <div class="navbar-items">
          <ul>
            <li class="nav-item">
              <a class="nav-link" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#skills">Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Contact Us</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Nav'
}
</script>

<style scoped>
#nav {
  border-bottom: 1px solid #dee2e6;
}
.navbar{
  display: flex;
  padding: 15px 25px 15px 25px;
  justify-content: space-between;
  flex-wrap: wrap;
}
.brand {
  font-weight: 600;
  display: inline-block;
  line-height: inherit;
  white-space: nowrap;
  padding-right: 20px;
  color:royalblue;
}
ul {
  display: flex;
  flex-direction: row;
  margin-top: 0;
  list-style: none;
  padding-left: 0;
  margin-bottom: 0;
}
.nav-link {
  text-decoration: none;
  padding-right: 20px;
  align-items: center;
  color: #2c3e50;
}
.nav-link:hover {
  font-weight: 600;
}
</style>
