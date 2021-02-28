<template>
    <div class="hero-content-container">
        <h1>Yo</h1>
        <h2>yooo</h2>
        <h6>ayayayyaya</h6>

    </div>
</template>

<script>
export default {
    name: 'HeroContent'
}
</script>

<style scoped>
.hero-content-container {
    margin: 5rem;
    display: grid;
    grid-template-columns: 2fr 1fr;
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

