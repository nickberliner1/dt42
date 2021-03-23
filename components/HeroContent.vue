<template>
    <div class="hero-content-container">
        <div class="heading">
            <h1 class="yo">Yo</h1>
			<h6>ayayayyaya</h6>
        </div>
        <div class="spaceman">
			            <!-- <img class="space-man" src="~/assets/spaceman.svg" alt="" srcset=""> -->
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
    </div>
</template>

<script>
// const circle = document.querySelector('.progress-ring__circle');
// const radius = circle.r.baseVal.value;
// const circumference = radius * 2 * Math.PI;

// circle.style.strokeDasharray = `${circumference} ${circumference}`;
// circle.style.strokeDashoffset = circumference;

export default {
    name: 'HeroContent',
    methods: {
        
        setProgress(percent) {
            const offset = circumference - percent / 100 * circumference;
            circle.style.strokeDashoffset = offset;
        }
        
    },

}
// animate svg

</script>

<style scoped>

/* planet styling */

svg .full-circle {
    fill: #2d5d85;
}

svg .dark-side {
    fill: #051634;
    animation: spinning 2s infinite;
    animation-timing-function: linear;
}

linearGradient .light-stop {
    stop-color: #ace8dd;
}

linearGradient .dark-stop {
    stop-color: #1c471f;
}

@keyframes spinning {
    from {
    transform: rotate(deg);
  }
  to {
    transform: rotate(360deg);
  }
}
/* end of planet styling */


/* spaceman styling */
/* .purple-oval {
    stroke-dasharray: 2600;
    stroke-dashoffset: 2600;
    fill-opacity: 0;
    animation: fill-all 1s forwards;
}

svg:hover .purple-oval {
    animation: unfill 1s;
}

@keyframes fill-all {
    to {
        fill-opacity: 1;
    }
}

@keyframes unfill {
    to {
        fill-opacity: 0;
    }
}

polygon {
    box-shadow: 10px 15px 25px 15px #ace8dd8f;
    fill: red;
}

.shoulder-pads {
    fill: #2d5d85;
}

.planets {
    fill: #ace8dd8f;
}

svg path {
    stroke-dasharray: 200;
    stroke-dashoffset: 200;
}

.spaceman {
    margin: 2em;
    display: block;
    margin: auto;
}
.spaceman-svg {
    filter: drop-shadow( 10px 15px 25px #ace8dd);
} */
/* end of spaceman styling */



.hero-content-container {
    margin: 5rem;
    display: grid;
    grid-template-columns: 1fr 2fr;
    grid-template-rows: 1fr 1fr;
    padding: 2rem;
} 

.heading {
	display: flex;
	flex-direction: column;
	justify-content: space-evenly;
    transition: transform 0.2s ease-in-out;
}

.heading:hover {
    transform: translate(0px, -20px);
    /* position: relative;
    transition: 0.2s ease-in-out; */
}

h1, h2, h6 {
    background-color: rgb(236, 236, 236);
    /* border: 1px solid rgb(128, 128, 128); */
    border-radius: 15px;
    padding: 15px;
    box-shadow: 10px 15px 25px 15px #ace8dd8f;
}

</style>

