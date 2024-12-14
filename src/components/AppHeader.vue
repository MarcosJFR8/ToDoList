<script setup lang="ts">

</script>

<template >
    <header>
        <h1>
            <span class="icon" aria-hidden="true">To do</span>
        </h1>
        <p>Mi lista de tareas en Vue</p>
    </header>
</template>

<style scoped>
    header{
        border-bottom: #000 1px solid;
        background-color: #fff;
    }
    header::after{
        content:"";
        display: block;
        height: 1px;
        box-shadow: 0px 0px 10px 0px rgb(0, 0, 0);
    }
    p{
        color: #000000;
    }
    h1{
        font-size: 2rem;
        color: #333;
    }
    h1 .icon {
        font-size: 1rem;
        vertical-align: bottom;
    }

</style>