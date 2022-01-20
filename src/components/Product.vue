<template>
    <div class="product">
        <div class="thumb">
            <img :src="src" :alt="alt">
        </div>
        <h2>{{series}}</h2>
    </div>
</template>

<script>
export default {
    name: "Product",
    props: {
        src: String,
        alt: String,
        series: String,
    }
}
</script>

<style lang="scss" scoped>
    .product{
            flex-basis: calc(100% / 6);
            .thumb{
                height: 200px;
                overflow: hidden;
            }
            h2{
                color: white;
                font-size: 1.3em;
                margin-top: 7px;
                margin-bottom: 15px;
                font-weight: 500;
            }
        }
</style>