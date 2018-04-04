<template>
  <div>
        <h2>Join our community</h2>
        <form action="">
            <input type="text" placeholder="Enter your email address" name="" id="">
            <button type="submit">Submit</button>
        </form>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
    div {
        display: flex;
        flex-direction: column;
        background-image: url("../assets/comito.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center center;  
    }
    form,h2 {
        margin: auto;
    }

    form {
        height: 200px;
    }

</style>
