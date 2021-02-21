<template>
    <div>
        <div class="relative -mt-12 lg:-mt-24">
            <HeroContent />
            <img src="~assets/hero-wave.svg?inline" />
        </div>
    </div>
</template>

<script>
import HeroContent from './HeroContent';

export default {
    name: 'Hero',

    components: {
        HeroContent,
    }
}
</script>
