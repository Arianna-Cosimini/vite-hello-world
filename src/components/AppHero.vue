<script>
export default {
    name: "AppHero",
}
</script>

<template>
    <div class="hero">

        <div class="text-hero">
            <h1>Vite</h1>

            <h2> Next Generation Frontend Tooling</h2>

            <p>Get ready for a development environment that can finally catch up with you </p>


            <button type="button">Get Starded</button>

        </div>

        <div class="img-hero">
            <img src="../../img/1618197067vitejs.png" alt="">
           
        </div>
    </div>
</template>

<style>
.hero {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    transform: translatey(50%);

}

.text-hero {
    display: flex;
    flex-direction: column;
    align-items: start;
    line-height: 50px;
}

.text-hero h1 {
    font-size: 50px;
    margin-bottom: 0;
    background-image: linear-gradient(to right, #699ffc, #bc38fe);
    /* Colore sfumato */
    -webkit-background-clip: text;
    /* Applico la sfumatura al testo */
    -webkit-text-fill-color: transparent;
    /* Nascondo il colore del testo */
}

.text-hero h2 {
    font-size: 50px;
    margin: 0;
}

.text-hero p {
    font-size: 25px;
    color: #7d7e7e;
    line-height: 30px;
}

.text-hero button {
    padding: 10px 20px;
    border-radius: 15px;
    background-color: #747bff;
    border: 0;
}





</style>