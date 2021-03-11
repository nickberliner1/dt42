<template>
    <div class="hero-content-container">
        <div class="heading">
            <h1>Yo</h1>
        </div>
        <div class="atom">
            <!-- <img src="~/assets/atom.svg" alt="" srcset=""> -->
<svg class="atom-svg" id="e2d57332-5c77-46ba-a509-f532ebdeb05d" 
    data-name="Layer 2" xmlns="http://www.w3.org/2000/svg" 
    width="500" height="400" viewBox="0 0 772.72109 669.07003"
>
    <path class="outer-ring" stroke="#000000" stroke-width="6" d="M779.36054,541.37612c-114.14062,0-207-92.86035-207-207.00049s92.85938-207,207-207,207,92.85986,207,207S893.50117,541.37612,779.36054,541.37612Zm0-412.00049c-113.03711,0-205,91.9624-205,205s91.96289,205.00049,205,205.00049,205-91.96289,205-205.00049S892.39765,129.37563,779.36054,129.37563Z" 
    transform="translate(-213.63946 -115.46498)" fill="#e6e6e6"/>
    <path d="M779.36054,483.37612c-82.15918,0-149-66.84131-149-149.00049,0-82.15869,66.84082-149,149-149s149,66.84131,149,149C928.36054,416.53481,861.51972,483.37612,779.36054,483.37612Zm0-296.00049c-81.05566,0-147,65.94385-147,147s65.94434,147.00049,147,147.00049,147-65.94434,147-147.00049S860.41621,187.37563,779.36054,187.37563Z" 
    transform="translate(-213.63946 -115.46498)" fill="#e6e6e6"/>
    <path d="M779.36054,424.71743a90.34156,90.34156,0,1,1,90.3418-90.3418A90.44435,90.44435,0,0,1,779.36054,424.71743Zm0-178.68311a88.34156,88.34156,0,1,0,88.3418,88.34131A88.44164,88.44164,0,0,0,779.36054,246.03432Z" 
    transform="translate(-213.63946 -115.46498)" fill="#e6e6e6"/>
    <circle class="circle" cx="565.7211" cy="218.91089" r="45.87339" fill="#42f57b"/>
    <circle class="circle" cx="598.53905" cy="14.54522" r="14.54522" fill="#42f57b"/>
    <circle class="circle" cx="416.16438" cy="360.2739" r="14.54522" fill="#42f57b"/>
    <circle class="circle" cx="418.16438" cy="235.2739" r="14.54522" fill="#e6e6e6"/>
    <circle class="circle" cx="690.16438" cy="137.2739" r="14.54522" fill="#e6e6e6"/>
    <circle class="circle" cx="747.16438" cy="318.2739" r="14.54522" fill="#e6e6e6"/>
    <circle class="circle" cx="704.83104" cy="253.98191" r="14.54522" fill="#42f57b"/>
    <circle class="circle" cx="385.95507" cy="115.24289" r="14.54522" fill="#42f57b"/>
    <circle class="circle" cx="619.79745" cy="418.45478" r="14.54522" fill="#42f57b"/>
</svg>


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

.circle {
  stroke-dasharray: 1000;
  stroke-dashoffset: 1000;
  animation: dash 5s linear;
}

@keyframes dash {
  from {
    stroke-dashoffset: 1000;
  }
  to {
    stroke-dashoffset: 0;
  }
}



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

.atom {
    margin: 2em;
    display: block;
    margin: auto;
}

.circle:hover {
    fill: #0000ff;
}

</style>

