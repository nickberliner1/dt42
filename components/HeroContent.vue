<template>
    <div class="hero-content-container">
        <div class="heading">
            <h1>Yo</h1>
        </div>
        <div class="atom">
            <img src="~/assets/atom.svg" alt="" srcset="">
        </div>
        <h6>ayayayyaya</h6>

    </div>
</template>

<script>
export default {
    name: 'HeroContent'
}
// animate svg
</script>

<style scoped>

.hero-content-container {
    margin: 5rem;
    display: grid;
    grid-template-columns: 1fr 2fr;
    /* grid-template-rows: 1fr 1fr; */
    padding: 2rem;
}

h1, h2, h6 {
    background-color: white;
    border: 2px solid white;
    border-radius: 15px;
    /* -webkit-text-stroke: 1px black; */
    /* text-shadow: 3px 1px 2px rgb(255, 255, 255); */
}

</style>

