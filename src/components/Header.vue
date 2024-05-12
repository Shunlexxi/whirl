<script setup lang="ts">

</script>

<template>
  <div class="header_container">
    <header>
      <div class="logo_wrapper">
        <img id="logo" src="/Logo.svg" class="logo" alt="Whirl logo" />
      </div>

      <div class="navigation">
        <ul id="header-list">
          <li id="header-link"><a href="#">Bridge NFT</a></li>
          <li id="header-link"><a href="#">Transaction</a></li>
        </ul>
      </div>

      <span id="header-opts">
        <img class="EvmDropdown" src="/EvmDropdown.png" alt="EvmDropdown">
        <img class="Wallet" src="/Wallet.png" alt="Wallet">
        <img class="LightModeButton" src="/LightModeButton.png" alt="LightModeButton">
      </span>
    </header>
  </div>
</template>

<style scoped>
.header_container {
  display: flex;
  justify-content: center;
}

header {
  width: 1440px;
  max-width: 90%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 90px;
}

#logo {
  height: 34px;
}

#header-list {
  display: flex;
  list-style-type: none;
  gap: 60px;
}



.navigation {
  width: 800px;
}

a {
  text-decoration: none;
  color: white;
}

#header-opts {
  display: flex;
  gap: 20px;
  align-items: center;

}

.Wallet {
  width: 24px;
  height: 24px;
}
</style>
