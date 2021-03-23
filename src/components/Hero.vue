<template>
    <div class='hero'> 
        <div class='hero__title'>Oyster Bay</div>
        <div class='hero__subtitle'>Resident Dashboard</div>
        <div class='hero__cta'>Learn More</div>
    </div>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .hero {
        align-items: flex-start;
        background-image: url('~@/assets/images/hero.png');
        background-size: cover;
        display: flex;
        flex-direction: column;
        height: 90vh;
        justify-content: center;
        width: 100%;
    }

    .hero__title {
        color: white;
        font-size: 50px;
    }

    .hero__subtitle {
        font-size: 30px;
        color: white;
    }
</style>
