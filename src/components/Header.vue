<template>
    <div class="header">
        <div class="links">
            <div class="ava">
                <div class="avatarka"><img src="../assets/avatar.png" alt=""></div>
            </div>
        </div>
        <div class="rehts">
            <h1 class="name">Артем Карпов</h1>
            <p class="disc">
                Привет! Я разработчик из Германии. Создаю креативные сайты и игры. </p>
        </div>
    </div>
</template>
<style scoped>
.links {
    margin: 30px;
}

.header {
    display: grid;
    grid-template-columns: 1fr 2fr;
}
.name{
    margin: 0;
}

.avatarka img {
    width: 100%;
}

.avatarka {
    border: 2px solid black;
    border-radius: 50%;
    background: rgb(51,49,49);
background: radial-gradient(circle, rgba(51,49,49,1) 0%, rgba(121,119,119,1) 58%, rgba(182,182,182,1) 100%);
}
.rehts{
    display: flex;
    justify-content: center;
    flex-direction: column;
}
</style>
