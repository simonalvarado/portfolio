<template>
  <div>
    <nav class="nav-bar">
      <ul class="items-box">
        <div id="a">
          <span to="" class="nav-item">
            <a
              href="https://fancy-silk-4a4.notion.site/Projects-e36e8e682f4e48228c9856169af3a82e"
              target="_blank"
              class="nav-text"
              >Projects</a
            >
          </span>
        </div>

        <div class="hide" id="b">
          <router-link to="/photography" class="nav-item">
            <span text class="nav-text">Photography</span>
          </router-link>
        </div>

        <div id="c">
          <router-link to="/contact" class="nav-item">
            <span class="nav-text">Contact</span>
          </router-link>
        </div>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.nav-bar {
  width: 100%;
  height: 10vh;
  background: black;
}

.items-box {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  width: 100vw;
  height: 100%;
  padding-left: 85px;
  padding-right: 85px;
}

.nav-item {
  text-decoration: none;
  padding-left: 6px;
  padding-right: 6px;
  font-size: 15px;
  font-family: "Basis";
  color: #ffffff;
  opacity: 0.8;
  transition: 0.3s;
}

.nav-text {
  text-decoration: none;
  color: #ffffff;
}

.nav-item:hover {
  opacity: 1;
}

.hide {
  display: none;
}
</style>
