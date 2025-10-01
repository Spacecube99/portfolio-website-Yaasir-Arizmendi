<template>
    <div class="container">
        <div class="column left-column">
            <h1>Cell:</h1>
            <h3>402-276-8327</h3>
        </div>
        <div class="column right-column">
            <h1>Email:</h1>
            <h3>arizmendiyaasir@gmail.com</h3>
        </div>
    </div>
</template>

<style>

    .column {
        flex: 1;
        padding: 10px;
        box-sizing: border-box;
    }

    .left-column {
        display: flex;
        flex-direction: row;
    }

    .right-column {
        display: flex;
        flex-direction: row;
    }

    h1 {
        color: black;
        display: flex;
        justify-content: center;
    }

    h1:nth-of-type(2) {
        display: flex;
        justify-content: center;
    }

    h3:nth-child(2) {
        color: black;
        margin-top: auto;
        margin-bottom: auto;
        padding-left: 2rem;
    }
</style>