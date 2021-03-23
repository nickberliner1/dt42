<template>
    <div>
        <nav class="navbar">
        <ul>
            <nuxt-link to="/" class="link">Home</nuxt-link>
            <nuxt-link to="/Circles" class="link">About</nuxt-link>
            <nuxt-link to="/" class="link">Events</nuxt-link>
            <nuxt-link to="/" class="link">Create Event</nuxt-link>
        </ul>
        </nav>
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
    background-color: rgba(179, 179, 179, 0.445);
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