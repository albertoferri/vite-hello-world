<!-- --------QUI VA I TUOI SCRIPT JS LEGATI A QUESTO COMPONENTS IN PARTICOLARE-------- -->
<script>

    // ----------

</script>

<!-- --------QUI VA L'HTML-------- -->
<template>

    <div class="container">
        <h2>JUMBOTRON</h2>
        <hr>
        <p id="section">
            Benvenuto nel Jumbotron!
            Scopri di più sul nostro prodotto o servizio in questa area di presentazione.
        </p>
        <button>ESEGUI</button>
    </div>
        
    
</template>



<!-- --------QUI VA IL CSS-------- -->
<style scoped>

.container{
    width: 900px;
    background-color: #191919;
    border-radius: 0.4rem;
    padding: 20px 30px;
    margin: auto;
    font-size: 20px;
    box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
}

button{
    background-color: rgb(192, 201, 20);
    border: none;
    color: #2a3036;
    padding: 12px 30px;
    font-size: 1.2rem;
    font-weight: bold;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 0.3rem;
}

button:hover{
    background-color: greenyellow;
    transition: .3s ease-in-out;
}

button:not(:hover){
    background-color: rgb(192, 201, 20);
    transition: .3s ease-in-out;
}

</style>