<template>
  <section class="section-content">
    <h3 class="title">{{ title }}</h3>
    <div class="content-wrapper">
      <slot name="icon" />
      <p class="content">{{ content }}</p>
    </div>
  </section>
</template>

<script setup lang="ts">
defineProps<{ title: string; content: string }>();
</script>

<style>
.section-content {
  color: #000;
  width: calc((100% - (2 * var(--section-gap))) / 3);
  min-width: 470px;
}

.section-content .title {
  font-weight: 600;
  margin-bottom: 15px;
  font-size: 2.4rem;
}

.section-content .content-wrapper {
}

.content-wrapper img {
  float: left;
}

@media screen and (max-width: 1200px) {
  .section-content {
    min-width: 330px;
  }
}

@media screen and (max-width: 900px) {
  .section-content {
    min-width: 100%;
  }
}
</style>
