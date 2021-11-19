<template>
    <header class="header">
        <div class="containers">
        <div class="logo">
            <h2>Pokemon</h2>
        </div>
        <nav class="menu">
            <input type="text" class="form-control" placeholder="Search...">
        </nav>
        </div>
    </header>
</template>

<style scoper>

    h1, h2, h3, h4, h5, h6 {
        font-family: "Fjalla One";
    }

    .header {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 70px;
        background-color: rgb(233, 227, 227);
    }

    .logo h2 {
        font-size: 40px;
        font-weight: 600;
    }

    .menu input {
        border: 1px solid rgb(235, 230, 230);
        border-radius: 5px;
        width: 300px;
        padding: 8px 10px;
    }

    .menu input::placeholder {
        font-size: 22px;
    }

    .containers {
        max-width: 1500px;
        display: inherit;
        align-items: inherit;
        justify-content: inherit;
        height: inherit;
        margin: 0 auto;
        flex: 1;
    }
    
</style>