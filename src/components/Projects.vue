<template>
    <div class="projects">
        <div class="header">
            <h2 class="ski"><i class="bi bi-robot"></i> Проекты <i class="bi bi-robot"></i>
            </h2>
        </div>
        <div class="project" v-for="project in projectsData">
            <a class="links" :href="project.link">
                <img class="imge" :src="project.imge" alt="">
            </a>
            <div class="rehts">
                <h3 class="header">{{ project.title }}</h3>
                <p>{{ project.beshreibung }}</p>
                <a :href="project.link">Перейти</a>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.links img {
    border: 2px solid black;
    width: 100%;
    border-radius: 20px;
    object-fit: contain;
    object-position: center;
}

.header {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    border-bottom: 2px solid black;
}

.projects {
    border: 2px solid black;
    border-radius: 20px;
    margin-top: 100px;
}

.project {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;
    text-align: center;
    padding: 20px 10px;
    @media (max-width: 600px) {
        grid-template-columns: 1fr;
        gap: 0;
        margin: 10px;
    }

}

.rehts {
    border: 2px solid black;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    border-radius: 20px;
}

.rehts h3 {
    padding-bottom: 20px;
}

.rehts p {
    padding: 5px;
    max-width: 300px;
}

.rehts a {
    border: 2px solid black;
    color: black;
    padding: 5px 10px;
    margin-bottom: 20px;
    border-radius: 5px;
}
</style>

<script setup>
import { projects } from '../data/projects';
import { ref } from 'vue';
const projectsData = ref(projects)
</script>
