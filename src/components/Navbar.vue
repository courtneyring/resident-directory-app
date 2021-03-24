<template>
    <div class="navbar">
        <div class='navbar__container'>

            <div class='navbar__logo'>
                OH
            </div>
            <div class='navbar__links'>
                <router-link :to="{ name: 'home' }" class='navbar__link'>Home</router-link>
                <router-link :to="{ name: 'about' }" class='navbar__link'>About</router-link>
                <router-link :to="{ name: 'about' }" class='navbar__link'>Directory</router-link>
                <router-link :to="{ name: 'about' }" class='navbar__link'>Contact</router-link>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    name: "MainNav",
    props: {
    }
};
</script>

<style lang='scss' scoped>

.navbar {
    background-color: white;
    height: 70px;
    left: 0px;
    
    position: fixed;
    top: 0px;
    width: 100%;
}

.navbar__container {
    @include container('xl');
    align-items: center;
    display: flex;
    justify-content: space-between;
    height: 100%;
    padding: 0px;
}

.navbar__link {
    color: $color-blue-dark;
    font-size: 20px;
    text-decoration: none;
    margin: 0px 15px;
}

.navbar__logo {
    color: $color-blue-dark;
    font-size: 30px;
}
</style>
