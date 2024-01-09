<script setup lang="ts">
import Sidebar from './components/Sidebar.vue';
import SectionContent from './components/SectionContent.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <div class="app-wrapper">
    <Sidebar />
    <div class="main-content">
      <div class="container">
        <div class="wrapper">
          <img class="logo" src="./assets/logo.svg" />

          <div class="main-section">
            <h4 class="title">Lorem ipsum dolor sit asmet?</h4>
            <p class="content">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
              tristique consequat placerat. Vestibulum auctor pellentesque sem,
              eu posuere erat hendrerit quis. Maecenas vel consequat turpis. Nam
              facilisis, ligula in mattis sodales, augue justo tristique nulla,
              sed lacinia ante eros ut mi. Morbi vitae diam augue. Aliquam vel
              mauris a nibh auctor commodo. Praesent et nisi eu justo eleifend
              convallis. Quisque suscipit maximus vestibulum. Phasellus congue
              mollis orci, sit amet luctus augue tristique eu. Donec vulputate
              odio neque, sed semper turpis pellentesque a.
            </p>
          </div>

          <div class="section-wrapper">
            <SectionContent
              title="Lorem ipsum dolor sit amet"
              content="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non dui sodales, faucibus libero ut, posuere felis. Donec imperdiet suscipit accumsan. Aenean consequat condimentum velit ut tempor. Nam porta massa in metus bibendum congue. Pellentesque ultrices liquam egestas nunc at ullamcorper ultricies. Donec feugiat velit nulla, vel sodales est ullamcorper id. Aenean consequat condimentum velit ut tempor. Nam porta massa in metus bibendum congue. Pellentesque ultrices vestibulum mattis."
            >
              <template #icon>
                <img src="./assets/icon1.svg" />
              </template>
            </SectionContent>

            <SectionContent
              title="Lorem ipsum dolor sit amet"
              content="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non dui sodales, faucibus libero ut, posuere felis. Donec imperdiet suscipit accumsan. Aenean consequat condimentum velit ut tempor. Nam porta massa in metus bibendum congue. Pellentesque ultrices liquam egestas nunc at ullamcorper ultricies. Donec feugiat velit nulla, vel sodales est ullamcorper id. Aenean consequat condimentum velit ut tempor. Nam porta massa in metus bibendum congue. Pellentesque ultrices vestibulum mattis."
            >
              <template #icon>
                <img src="./assets/icon2.svg" />
              </template>
            </SectionContent>

            <SectionContent
              title="Lorem ipsum dolor sit amet"
              content="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non dui sodales, faucibus libero ut, posuere felis. Donec imperdiet suscipit accumsan. Aenean consequat condimentum velit ut tempor. Nam porta massa in metus bibendum congue. Pellentesque ultrices liquam egestas nunc at ullamcorper ultricies. Donec feugiat velit nulla, vel sodales est ullamcorper id. Aenean consequat condimentum velit ut tempor. Nam porta massa in metus bibendum congue. Pellentesque ultrices vestibulum mattis."
            >
              <template #icon>
                <img src="./assets/icon3.svg" />
              </template>
            </SectionContent>
          </div>
        </div>
      </div>
      <Footer />
    </div>
  </div>
</template>

<style scoped></style>
