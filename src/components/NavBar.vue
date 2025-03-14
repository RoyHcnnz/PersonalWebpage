<template>
    <div class="nav">
        <div class="text-logo"><p>&lt/> RUNGRY</p></div>
        <div class="nav-links">
            <p class="nav-link"><a href="#about">About</a></p>
            <p class="nav-link"><a href="#projects">Projects</a></p>
            <p class="nav-link"><a href="#contact">Contact</a></p>
        </div>
    </div>
</template>

<style scoped>
    a:hover {
        background-color: var(--color-background-mute);
    }

    .nav{
        width: 100vw;
        height: 70px;
        position: fixed;
        background: var(--vt-c-black);
        display: flex;
        padding: 0px 100px;
        align-items: center;
    }

    .text-logo{
        width: 50%;
        color: var(--vt-c-primary);
        font-family: "Chakra Petch", sans-serif;
        font-weight: bold;
        font-size: 24px;
    }

    .nav-links{
        width: 50%;
        display: flex;
        justify-content: flex-end;
        gap: 20px;
    }

    .nav-link{
        color: var(--vt-c-secondary);
        font-size: 24px;
        font-weight: bold;
    }
</style>