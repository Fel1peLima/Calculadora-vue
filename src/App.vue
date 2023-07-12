<template>

 <div id="app">
 <h1>Calculdora</h1>
 <ComponentsCalculator />
 </div>

</template>

<script>
import ComponentsCalculator from "./main/ComponentsCalculator"

export default {
    components: { ComponentsCalculator }
}
</script>

<style>
@font-face {
    font-family: "RobotoMono";
    src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
    font-family: "RobotoMono", monospace;
}

body {
    margin: 0;
}

#app {
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: #fff;
    background: linear-gradient(to right, rgb(93, 0, 129), rgb(10, 0, 150))
}
</style>