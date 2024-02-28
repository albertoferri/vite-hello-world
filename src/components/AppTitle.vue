<!-- --------QUI VA I TUOI SCRIPT JS LEGATI A QUESTO COMPONENTS IN PARTICOLARE-------- -->
<script>

    // ----------

</script>

<!-- --------QUI VA L'HTML-------- -->
<template>
    <div>
        <h1>LA MIA PRIMA APP CON VITE!</h1>
    </div>
</template>



<!-- --------QUI VA IL CSS-------- -->
<style scoped>

template{
    display: flex;
    justify-content: center;
}

h1{
    color: rgb(192, 201, 20);
    margin: 100px auto;
    padding: 20px 30px;
    border: 3px solid red;
    border-radius: 20px;
    border-color: rgb(192, 201, 20);
    text-align: center;
    width: 600px;
    cursor: wait;
    user-select: none;
}

h1:hover{
    color: greenyellow;
    transition: .3s ease-in-out;
}

h1:not(:hover){
    color: rgb(192, 201, 20);
    transition: .3s ease-in-out;
}

</style>