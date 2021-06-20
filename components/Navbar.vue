<template>
  <header class="header">
    <div class="header-content">
      <div class="header-logo">{LOGO}</div>
      <ul class="nav">
        <li class="nav-item">Beranda</li>
        <li class="nav-item">Tentang Kami</li>
        <li class="nav-item">Produk</li>
        <li class="nav-item">Point</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style>
  .header{
    width: 100%;
    display: flex;
    overflow: hidden;
    align-items: center;
    justify-content: center;
    padding: 20px 50px;

    /* border: 1px solid red; */
  }
  .header-content{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .nav{
    display: flex;
    justify-content: space-evenly;
  }
  .nav .nav-item {
    margin: auto 15px;
  }
</style>
