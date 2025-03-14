<script setup lang="ts">
import KeywordBubble from './KeywordBubble.vue';
</script>

<template>
    <div class="project-card">
        <div class="project-name">
            <slot name="project-name">
                <h2>Coming soon ...</h2>
            </slot>
        </div>
        <div class="project-description">
            <slot name="project-description">
                <p>More exciting projects are coming soon!</p>
            </slot>
        </div>
        <div class="project-keywords">
            <slot name="project-keywords">
                <KeywordBubble>Inspiration</KeywordBubble>
                <KeywordBubble>Diligence</KeywordBubble>
            </slot>
        </div>
        <div class="project-link">
            <slot name="project-link">
                <a>View Project →</a>
            </slot>
        </div>
    </div>
</template>

<style scopled>
    .project-card{
        width: 650px;
        height: 290px;
        border-radius: 15px;
        border-width: thin;
        border-style: solid;
        border-color: var(--vt-c-primary);
        background: #090B18;
        padding: 15px;


        display: flex;
        flex-direction: column;
        gap: 20px;

        color:aliceblue;
    }

    .project-name{
        font-size: 22px;
        font-weight: 700;
        color: var(--vt-c-primary);
    }

    .project-description{
        font-size: 20px;
        color: var(--vt-c-secondary);
    }

    .project-keywords{
        display: flex;
        gap: 15px;
    }

    .project-link{
        font-size: 20px;
        font-weight: 500;
        color: var(--vt-c-primary)
    }
</style>