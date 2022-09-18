<script>
import BaseLayout from '../layouts/BaseLayout.vue'
export default {
  components: { BaseLayout },
    
}
</script>
<template>
    <base-layout>
        <h1>teste de PageFoo.vue</h1>
        <router-link to="/">Home</router-link>        
    </base-layout>
</template>