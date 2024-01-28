<template>
    <div class="skills">
        <div class="header">
            <h2 class="ski"><i class="bi bi-browser-chrome"></i> Контакты <i class="bi bi-browser-chrome"></i></h2>
        </div>
        <div class="grid">
            <ul class="info">
                <li><a href="">Дискорд</a></li>
                <li><a href="">Телеграмм</a></li>
                <li><a href="">vufka33@gmail.com</a></li>
                <li><a href="">+49151520495185</a></li>
            </ul>
            <div class="form">
                <h3>Обращяйтесь ко мне</h3>
                <textarea></textarea>
                <button>Отправить</button>
            </div>
        </div>
    </div>
</template>

<style scoped>
.skills {
    border: 2px solid black;
    border-radius: 20px;
    margin-top: 50px;
    margin-bottom: 50px;
}

.header {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    border-bottom: 2px solid black;
}

.item img {
    width: 80px;
    height: 80px;
    object-fit: contain;
    object-position: center;
}

.item p {
    text-align: center;
    margin: 0;
}

.items {
    /* display: grid;
    grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
    gap: 45px; */
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-wrap: wrap;
}
.item{
    min-width: 150px;
    display: flex;
    text-align: center;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    margin: 20px 0 10px 0;
}
.grid{
    display: grid;
    grid-template-columns: 1fr 2fr;
}
.form{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-left: 2px solid black;
}

.form textarea{
    width: 80%;
    height: 120px;
    background-color: rgb(255, 255, 255);
    border: 2px solid black;
    padding: 10px;
    border-radius: 10px;
}

.form button{
    border: 2px solid black;
    color: black;
    padding: 5px 10px;
    margin-bottom: 20px;
    border-radius: 5px;
    background-color: rgba(0, 0, 0, 0);
    margin-top: 10px;
}

.info{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    font-size: 20px;
    gap: 15px;
    padding: 0;
    margin: 0 10px;

}

.info li{
    list-style: none;
    text-align: center;
    border: 2px solid black;
    border-radius: 20px;
    padding: 10px 25px;
    width: 100%;
    box-sizing: border-box;

    
}

</style>

<script></script>