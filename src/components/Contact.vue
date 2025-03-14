<script setup lang="ts">
import IconGithub from './icons/IconGithub.vue';
import IconLinkedIn from './icons/IconLinkedIn.vue';
import IconEmail from './icons/IconEmail.vue';
</script>

<template>
    <div class="contact" id="contact">
        <div class="title c-cyberpunk"><h1>Together, let's create something amazing!</h1></div>

        <a href="https://github.com/RoyHcnnz">
            <div class="contact-method">   
                <div><IconGithub /></div><div>RoyHcnnz</div>
            </div>
        </a>
        
        <a href="https://www.linkedin.com/in/run-h-b89b44215/">
            <div class="contact-method">
                <div><IconLinkedIn /></div><div><p>LinkedIn</p></div>
            </div>
        </a>

        <a href="mailto:rhuangcnnz@gmail.com">
            <div class="contact-method">
                <div><IconEmail /></div><div><p>rhuangcnnz@gmail.com</p></div>
            </div>
        </a>
    </div>
</template>

<style scoped>


    .contact{

        width: 100vw;
        padding: 300px 10px;

        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .title{
        font-size: 36px;
        font-weight: bold;
        text-align: center;
        margin-bottom: 30px;
    }

    .contact-method{
        width: fit-content;
        color: var(--vt-c-primary);
        display: flex;
        justify-content: center;

        font-size: 20px;
    }
</style>