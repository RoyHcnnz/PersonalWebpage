<script setup lang="ts">
import ProjectCard from './ProjectCard.vue';
import KeywordBubble from './KeywordBubble.vue';
</script>

<template>
    <div class="projects-section" id="projects">
        <div class="title c-cyberpunk">
            <h1>Featured Projects</h1>
        </div>
        <div class="projects-cards">
            <div class="projects-row">
                <ProjectCard />
            </div>
        </div>
    </div>
</template>

<style scoped>
    .projects-section{
        padding: 20vh 10px;
        width: 100vw;
        display: flex;
        flex-direction: column;
        align-items: center;
        gap: 70px;
    }

    .title{
        font-size: 40px;
        font-weight: bold;
    }

    .projects-cards{
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 50px;
    }

    .projects-row{
        display: flex;
        justify-content: center;
        gap: 30px;
    }

</style>