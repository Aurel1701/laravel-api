<template>
  <div>
    <nav class="nav justify-content-center">
      <a class="nav-link active" href="#">home</a>
      <a class="nav-link" href="#">about</a>
      <a class="nav-link" href="#">posts</a>
    </nav>
    <router-view></router-view>
  </div>

</template>

<script>
export default {
  name: "App",
  data() {
    return {
      menu_items: [
        {
          route_name: 'home',
          route_text: 'Home'
        },
        {
          route_name: 'about',
          route_text: 'About'
        },
        {
          route_name: 'posts',
          route_text: 'Posts'
        },
      ]
    }
  }
}
</script>
