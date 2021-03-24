<template>
    <div class="home">
        <Hero />
        <div class="section home__intro">
            <div class="section__container">
                <img src="@/assets/images/house.jpg" class="home__image" />
                <div class="home__text">
                    <div class="home__title">About Us</div>
                    <div class="home__body">
                        <p>
                            Lorem ipsum dolor sit amet leo ultrices posuere orci
                            magna purus, dictum justo elit, pulvinar nulla a
                            lorem pretium sit amet quam. Donec nec malesuada
                            fames ac accumsan vitae, mollis nibh pulvinar
                            vulputate.
                        </p>
                        <p>
                            Integer congue a felis a auctor. Donec non sagittis
                            purus. Aenean id nulla metus. Aliquam ut velit at
                            ligula consectetur rhoncus. Nullam fringilla odio a
                            sem gravida convallis. Nulla sagittis quam leo, non
                            sodales lectus pretium a. Nullam tristique
                            sollicitudin augue, vel interdum ligula congue a.
                            Etiam vitae fermentum quam. Aenean gravida tristique
                            dui nec ornare etiam sit
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
// @ is an alias to /src
import Hero from "@/components/Hero.vue";
// import SectionText from "@/components/SectionText.vue";

export default {
    name: "Home",
    components: {
        Hero,
        // SectionText,
    },
};
</script>



<style lang='scss' scoped>
.home__intro > .section__container {
    display: flex;
    justify-content: space-between;
}

.home__image,
.home__text {
    width: 48%;
}

.home__text {
    color: $color-blue-dark;
    font-size: 20px;
    line-height: 30px;
    text-align: left;
}

.home__title {
    font-size: 40px;
    font-weight: bold;
    margin-bottom: 50px;
}
</style>