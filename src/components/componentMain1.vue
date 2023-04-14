<template>
    <div class="d-flex flex-column align-content-center justify-content-center py-2">
        <div class="gi-img mb-2">
            <img :src="thumb" :alt="type">
        </div>
        <h6 class="text-light text-center">{{ series }}</h6>
        
    </div>
</template>

<script>
export default {
    props: {
        thumb: 'string',
        series: 'string',
        type: 'string'
    }
}
</script>

<style lang="scss" scoped>
.gi-img {
    width: 200px;
    height: 200px;

    img {
        width: 100%;
        height: 100%;
        object-fit: contain;

    }
}
</style>