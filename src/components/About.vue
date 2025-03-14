<template>
    <div class="about-wrapper" id="about">
        <div class="about">
            <div class="c-cyberpunk">
                <h1 class="title">Title</h1>
            </div>
            <p class="description">
                Description
            </p>
            <div class="nav-buttons">
                <a href="#contact">
                    <button class="get-in-touch-button">Get In Touch</button>
                </a>
                <a href="#projects">
                    <button class="view-projects-button">View Projects</button>
                </a>
            </div>
        </div>
    </div>
</template>

<style scoped>
    button{
        width: 230px;
        height: 70px;
        padding: 20px;
        border-radius: 15px;
        font-size: 24px;
        color: var(--vt-c-white-soft);
        background: none;
        border: 0;
        transition: 0.4s;
        cursor: pointer;
    }

    .view-projects-button{
        border: 2px;
        border-color: var(--vt-c-primary);
        border-style: solid;
    }    
    
    .view-projects-button:hover{
        background: var(--vt-c-black-mute);
        border-color: var(--vt-c-primary-dark);
    }

    .get-in-touch-button{
        background: var(--vt-c-primary);
    }

    .get-in-touch-button:hover{
        background: var(--vt-c-primary-dark);
    }

    .nav-buttons{
        padding-left: 5px;
        display: flex;
        gap: 50px;
    }

    .about-wrapper{
        width: auto;
        height: 100vh;
        background: var(--vt-c-black-secondary);
        padding-left: 10%;
        display: flex;
    }

    .about{
        width: 50%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 56px;
    }

    .title{
        color: var(--vt-c-primary);
        font-size: 64px;
        font-weight: 800;
    }

    .description{
        color: var(--vt-c-secondary);
        font-size: 32px;
        font-weight: 600;
    }
</style>