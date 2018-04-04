<template>
    <div>
        <h1>Circassian Benevolent Association</h1>
        <img src="../assets/header.jpg" alt="Circassian Benevolent Association flyover">

        <p>The CBA is always looking for volunteers!</p>

        <h2>NARTS DANCE ENSEMBLE</h2>
        <h2>AMIN SAMKOUGH SCHOOL</h2>
        <h2>SPORTS</h2>

        <button class="buttons">Donate Now</button>
        <button class="buttons">Get Envolved</button>

        <Signup />

    </div>
</template>

<script>
import Signup from './EmailSignup.vue'
export default {
    components: {
        Signup,
    }
}
</script>

<style scoped>
    .buttons {
        background-color: #27ae60;
        color: white;
        text-transform: uppercase;
        font-size: 1rem;
        font-weight: bold;
        width: 100px;
        height: 40px;
        margin-left: 20px;
    }
    img {
        width: 100%;
        height: auto;
    }
    h1,h2 {
        margin-left: 1rem;
    }
</style>
