<template>
  <div class="navbar">
    <div class="logo-header">
      <div class="logo-header-icon">
        <!-- <i class="fas fa-prescription-bottle"></i> -->
        <!-- <i class="fas fa-box-open"></i> -->
        <i class="fas fa-bong"></i>
      </div>
      <div class="logo-header-label">minickup</div>
    </div>
    <div class="icon">
      <i class="fas fa-cog"></i>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.navbar {
  -webkit-app-region: drag;
  -webkit-user-select: none;
  position: fixed;
  width: 100vw;
  top: 0;
  left: 0;
  z-index: 1;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 60px;
  background: #fa776d;
}

.navbar .logo-header {
  display: flex;
  color: #fff;
  align-items: center;
  justify-content: center;
}

.navbar .logo-header-icon {
  font-size: 25px;
  font-weight: 300;
}

.navbar .logo-header-label {
  font-family: "Roboto", "sans serif";
  padding-left: 10px;
  font-size: 30px;
  font-weight: 300;
  letter-spacing: 3px;
}

.navbar .icon {
  position: absolute;
  display: flex;
  right: 0px;
  align-items: center;
  justify-content: center;
  color: #fff;
  font-size: 25px;
  width: 60px;
  height: 60px;
  box-sizing: border-box;
  cursor: pointer;
}

.navbar .icon:hover {
  color: #fff;
  background: #0ca5fb;
  font-size: 25px;
  padding: 0px 0px;
  width: 60px;
  height: 60px;
}
</style>