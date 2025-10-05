<template>
    <div>
        <h3>I am a front-end developer that would
        like to use my skills to integrate
        any experience I earn with AI to adapt
        with modern tech. I like learning how to code, and I would
        like to learn more languages to be flexible
        and proficient.
        </h3>
    </br>
    <h3>
        Code can do good things, understanding how to code is better.
    </h3>
        <img src="/public/yaasir_Portfolio_No_Background.png" alt="Picture of Yaasir Arizmendi"></img>
    </div>
</template>

<style scoped>
h3 {
    color: black;
    display: flex;
    text-align: center;
    padding-right: 2rem;
}

img {
    background: green;
    width: 25rem;
    height: 40rem;
    display: flex;
    margin-left: auto;
    margin-right: auto;
    border-style: solid;
    border-width: 20px;
    animation: shine 5s linear infinite;
}

@keyframes shine {
    0% {
        border-image: linear-gradient(0deg, yellow, gray) 1;
    }
    50% {
        border-image: linear-gradient(180deg, yellow, gray) 1;
    }
    100% {
        border-image: linear-gradient(360deg, yellow, grey) 1;
    }
}
</style>