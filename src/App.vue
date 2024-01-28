<script setup>
import Navbar from './components/Navbar.vue';
import Header from './components/Header.vue';
import Skills from './components/Skills.vue';
import Projects from './components/Projects.vue';
import Contact from './components/Contact.vue';
</script>

<template>
    <Navbar />
    <div class="container">
        <Header />
        <Skills />
        <Projects />
        <Contact />
    </div>
</template>

<style scoped>
.container {
    max-width: 1200px;
    margin: 0 auto;

}
</style>
