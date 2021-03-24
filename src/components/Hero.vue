<template>
    <div class="hero">
        <div class="hero__container">
            <div class="hero__text">
                <div class="hero__eyebrow">Oyster Harbor</div>
                <div class="hero__title">Resident Dashboard</div>
                <!-- <div class="hero__description">
                    Integer congue a felis a auctor. Donec non sagittis purus.
                    Aenean id nulla metus. Aliquam ut velit at ligula
                    consectetur rhoncus. Nullam fringilla odio a sem gravida
                    convallis. Nulla sagittis quam leo, non sodales lectus
                    pretium a. Nullam tristique sollicitudin augue, vel i
                </div> -->
                <div class="hero__cta" @click="goToAbout()">Learn More</div>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: "Hero",

    methods: {
        goToAbout: function () {
            this.$router.push("about");
        },
    },
};
</script>

<style lang='scss' scoped>
.hero {
    background-image: url("~@/assets/images/hero12.jpeg");
    background-position: center;
    background-size: cover;
    height: 85vh;
    width: 100%;
}

.hero__container {
    @include container("xl");
    align-items: flex-start;
    display: flex;
    height: 100%;
    flex-direction: column;
    justify-content: center;
    padding: 0px;
}

.hero__text {
    align-items: flex-start;
    display: flex;
    flex-direction: column;
    // margin-bottom: 200px;
}

.hero__title {
    color: $color-blue-dark;
    font-size: 85px;
    font-weight: bold;
    margin-bottom: 50px;
    text-transform: uppercase;
}

.hero__eyebrow {
    font-size: 45px;
    color: $color-blue-light;
    margin-bottom: 20px;
}

.hero__cta {
    background-color: $color-blue-light;
    color: white;
    cursor: pointer;
    font-size: 26px;
    padding: 10px 20px;
}
</style>
