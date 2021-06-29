<template>
  <div class="about pa-6">
    <h1>About {{appTitle}}</h1>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet, quaerat placeat iusto sint ab provident maxime iste omnis explicabo asperiores aspernatur commodi autem quae, qui cum ipsa ipsum quo. Autem.</p>
    <p>Disini harusnya: {{appTitle}}</p>
  
  </div>
</template>
<script>
export default {
 data() {
   return {

   }
 },
 computed: {
   appTitle() {
     return process.env.VUE_APP_TITLE
   }
 },
 methods: {
  
 }
}
</script>