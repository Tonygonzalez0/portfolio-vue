<template>
    <section class="hero is-medium">
        <div class="hero-body">
            <div class="container has-text-centered">
                <!-- TODO: Add the typing effect -->
                <h1 class="title is-1 has-text-primary">Front-end Developer🖥</h1>
                <img :src="Image" alt="">
            </div>
        </div>
    </section>
</template>

<script>
import Image from '../assets/hero-image.jpg'
export default {
    data: function () {
        return {
            Image: Image
        }
    }
}
</script>


<style lang="scss" scoped>
    .hero {
        padding-top: 2rem;
    }
</style>

