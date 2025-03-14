<template>
    <div class="bubble">
        <div class="keyword">
            <slot></slot>
        </div>
    </div>
</template>

<style scoped>
    .bubble{
        width: fit-content;
        padding: 3px 8px;
        background: #091E28;
        border-radius: 15px;
    }

    .keyword{
        font-size: 18px;
        color: var(--vt-c-primary);
    }
</style>