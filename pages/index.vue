<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt Test</NuxtLink>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
        <a href="/about">normal link</a>
      </nav>
    </header>

    <h2>Home</h2>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Velit, cum animi. Iure, aspernatur, ab exercitationem distinctio sed itaque nostrum esse, voluptatem error inventore dolor mollitia facilis dolore. Perferendis, aliquam explicabo.</p>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo sequi qui excepturi id veritatis aliquid, a facilis numquam fuga odit earum voluptatem enim amet? Accusamus cupiditate qui quibusdam nostrum esse.</p>
  </div>
</template>

<script setup>

</script>

<style scoped>
  h2{
    margin-bottom: 20px;
    font-size: 36px;
  }
  p{
    margin:20px 0;
  }
</style>