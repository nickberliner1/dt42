<template>
    <div>
        <nav class="navbar">

            <div class="logo">

                <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" height="119.8" preserveAspectRatio="xMidYMid meet" version="1.0" viewBox="-48.4 -6.6 372.9 119.8" width="372.9" zoomAndPan="magnify">
                <g>
                    <g>
                        <g id="change1_1">
                            <path class="full-circle" d="M175.2,52.3c0,28.9-23.4,52.3-52.3,52.3c-28.9,0-52.3-23.4-52.3-52.3C70.6,23.4,94,0,122.9,0 c0,0,0.1,0,0.1,0C151.8,0,175.2,23.4,175.2,52.3C175.2,52.2,175.2,52.3,175.2,52.3z" fill="#fdcc9a"/>
                        </g>
                        <g id="change2_1">
                            <path class="dark-side" d="M175.2,52.3c0,16.9-8.1,32.7-21.9,42.5c-27.3,9.5-57.1-4.9-66.6-32.1c-7.6-21.9,0-46.2,18.8-59.7 c27.3-9.6,57.1,4.7,66.7,32C174.2,40.6,175.2,46.4,175.2,52.3L175.2,52.3z" fill="#c19a74"/>
                        </g>
                        <linearGradient xmlns:xlink="http://www.w3.org/1999/xlink" gradientTransform="matrix(1 0 0 -1 0 114)" gradientUnits="userSpaceOnUse" id="a" x1="-55.659" x2="268.581" xlink:actuate="onLoad" xlink:show="other" xlink:type="simple" y1="-10.574" y2="95.346">
                            <stop class="light-stop" offset="0" stop-color="#fdcc9a"/>
                            <stop class="dark-stop" offset="1" stop-color="#f59d3d"/>
                        </linearGradient>
                        <path class="planet-ring" d="M72.9,67.2c0,0-121.3,43.2-50.9,44.6S324.5,8.6,270.1,12.9c-33.8,2.8-67.4,8.1-100.4,15.9 c0,0,23.6-0.4,41.3-3.4c52.8-9-26.3,39.3-162.6,69.2C11.4,100.4,72.9,67.2,72.9,67.2z" fill="url(#a)"/>
                    </g>
                </g>
                
                </svg>

            </div>




        <ul class="nav-links">
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
    padding: 1.7rem;
    /* background-color: rgba(179, 179, 179, 0.445); */
}

.link {
    background-color: rgba(255, 99, 71, 0.315);
    backdrop-filter: blur(20px) ;
}

/* logo styling */
svg {
    width: 12em;
    height: auto;
}

svg .full-circle {
    fill: #051634;
}

svg .dark-side {
    
    fill: #2d5d85;
}

linearGradient .light-stop {
    stop-color: #1c471f;
}

linearGradient .dark-stop {
    
    stop-color: #ace8dd;
}

/* end of logo styling */

.nav-links {
    display: flex;
    justify-content: flex-end;
    align-items: center;
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