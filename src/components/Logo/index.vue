<template>
  <h1 class="logo">
    <a href="/" :title="title">
      <img src="@/assets/images/marvel-logo.svg" :alt="title"/>
    </a>
  </h1>
</template>

<script>
  export default {
    name: 'Logo',
    props: {
      title: String
    }
  }
</script>
