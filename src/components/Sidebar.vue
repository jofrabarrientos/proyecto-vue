<template>
<div class="sidebar">
 <h2>Barra lateral</h2>
 <ul>
 <li><router-link to="/contador">Contador</router-link></li>
 <li><router-link to="/lista-de-tareas">Lista De Tareas</router-link></li>
</ul>
</div>

</template>

<script setup>

</script>

<style>
.sidebar {
    width: 200px;
    background-color: #f0f0f0;
    padding: 20px;
}
</style>