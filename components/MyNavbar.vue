<template>
    <div>
    
    <!-- <b-navbar type="dark" variant="dark">
        <b-navbar-nav class="navbar"> -->
    <nav class="navbar">
            <nuxt-link to="/" class="link">Home</nuxt-link>
            <nuxt-link to="/" class="link">About</nuxt-link>
            <nuxt-link to="/" class="link">Events</nuxt-link>
            <nuxt-link to="/" class="link">Create Event</nuxt-link>
    </nav>
        <!-- </b-navbar-nav>
    </b-navbar> -->
    </div>
</template>

<script>
export default {
    name: 'MyNavbar'
}
</script>

<style scoped>
.navbar {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 1.7rem;
    background-color: none;
}

.link {
    margin-right: 5rem;
    color: black;
}

.link:hover {
    color: grey;
    text-decoration: none;
}
</style>