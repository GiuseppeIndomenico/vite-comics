<template>
    <div class="container d-flex justify-content-between">
        <div class="logo">
            <img class="img-fluid" src="../assets/img/dc-logo.png" alt="">
        </div>
        <ul class="d-flex align-items-center justify-content-center m-0">
            <li v-for="(link, index) in linksNav" class="p-3 d-flex align-items-center" :key="index">
                <a class="fw-semibold" :href="link.url">{{link.title }}</a>
            </li>

        </ul>
    </div>
</template>

<script>
export default {

    data() {
        return {
            linksNav: [
                {
                    title: 'Characters',
                    active: false,
                    url: '#'
                },

                {
                    title: 'Comics',
                    active: true,
                    url: '#'

                },

                {
                    title: 'Movie',
                    active: false,
                    url: '#'

                },

                {
                    title: 'TV',
                    active: false,
                    url: '#'

                },

                {
                    title: 'Games',
                    active: false,
                    url: '#'

                },

                {
                    title: 'Collectibles',
                    active: false,
                    url: '#'

                },

                {
                    title: 'Videos',
                    active: false,
                    url: '#'

                },

                {
                    title: 'Fans',
                    active: false,
                    url: '#'

                },

                {
                    title: 'News',
                    active: false,
                    url: '#'

                },
                {
                    title: 'Shop',
                    active: false,
                    url: '#'
                },



            ]
        }
    }

}
</script>

<style lang="scss" scoped>
.logo {
    width: 80px;
    height: 80px;
    margin: 20px;
}

ul {
    list-style: none;

    li {
        height: 100%;
        border-bottom: 3px inset transparent;
        

        &:hover {
            border-bottom: 3px inset #0d6efd;
            a {
                color: #0d6efd
            }
        }
        a {
            text-decoration: none;
            color: black;
         
        }
    }
}
</style>