<template>
  <div class="side-bar">
    <ul class="menu">
      <li
        v-for="(item, index) in ['Home', 'Services', 'News', 'Blog', 'Contact']"
        :key="index"
        :index="index"
        class="menu-item"
      >
        <span>{{ item }}</span>
      </li>
    </ul>
  </div>
</template>

<style>
.side-bar {
  display: flex;
  position: fixed;
  top: 0;
  left: 0;
  height: 100vh;
  width: var(--siderbar-width);
  background-color: #191718;
  overflow: hidden;
}

.menu {
  list-style: none;
  width: 100%;
}

.menu .menu-item {
  display: flex;
  align-items: center;
  padding: 12px 15px;
  border-bottom: 1px solid #aaaaaa;
  height: 44px;
  line-height: 44px;
  color: #aaaaaa;
  /* transition: background-color, color 0.15s; */
}

.menu .menu-item:hover {
  background-color: #5c5c5c;
  color: #fff;
}
</style>
