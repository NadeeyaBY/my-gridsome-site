<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/02.jpg" width="135" />
    
    <h1>Hello, world!</h1>

    <ul>
      <li><g-link to="/blog-html/blog-post-one">Blog Post </g-link></li>
    </ul>

    <p>
      เว็บไซต์นี้สร้างขึ้นเพื่อการศึกษาเรียนรู้ การใช้ Gridsome ซึ่งเป็นตัวช่วยในการสร้างเว็บไซต์ เป็นส่วนหนึ่งของ รายวิชา 240-420 และจะพัฒนาเพื่อใช้งานจริงในอนาคต
    </p>

    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
