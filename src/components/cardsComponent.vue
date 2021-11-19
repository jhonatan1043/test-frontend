<template>
    <div class="contenedor__cards">

        <div class="card">

        </div>
        <div class="card">

        </div>
        <div class="card">

        </div>
        <div class="card">

        </div>
        <div class="card">

        </div>
        <div class="card">

        </div>

    </div>
</template>

<style scoped>

.contenedor__cards {
    width: 70vw;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-evenly;
    
}
    .card {
        width: 350px;
        height: 350px;
        flex-shrink: 0;
        margin: 10px;
        box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
        border: 2px solid rgb(236, 230, 230);
        border-radius: 7px;
    }

    .card:hover {
        width: 353px;
        height: 353px;
    }
</style>