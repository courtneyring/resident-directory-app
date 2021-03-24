<template>
    <div class="text section">
        <div class="section__container">
            <div class="text__image">
                <img src='@/assets/images/house.jpg' />
            </div>
            <div class="text__content">
                <p>
                    Lorem ipsum dolor sit amet leo ultrices posuere orci magna
                    purus, dictum justo elit, pulvinar nulla a lorem pretium sit
                    amet quam. Donec nec malesuada fames ac accumsan vitae,
                    mollis nibh pulvinar vulputate.
                </p>
                <p>
                    Integer congue a felis a auctor. Donec non sagittis purus.
                    Aenean id nulla metus. Aliquam ut velit at ligula
                    consectetur rhoncus. Nullam fringilla odio a sem gravida
                    convallis. Nulla sagittis quam leo, non sodales lectus
                    pretium a. Nullam tristique sollicitudin augue, vel interdum
                    ligula congue a. Etiam vitae fermentum quam. Aenean gravida
                    tristique dui nec ornare etiam sit
                </p>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: "SectionText",
};
</script>

<style lang='scss' scoped>
.section.text {
    // background-color: $color-grey-light;
}

.section__container {
    display: flex;
    justify-content: space-between;
}

.text__image {
    width: 48%;

    & > img {
        height: auto;
        width: 100%;
    }
}

.text__content {
    font-size: 20px;
    line-height: 30px;
    text-align: left;
    width: 48%;
}
</style>
