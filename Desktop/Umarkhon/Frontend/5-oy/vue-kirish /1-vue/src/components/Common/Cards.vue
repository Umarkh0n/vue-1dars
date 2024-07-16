<template>
    <div class="cards ">
        <img :src="image" alt="">
        <h3>
            {{ head }}
        </h3>
        <p>
            {{ page }}
        </p>

    </div>
</template>

<script setup>
defineProps({
    image: String,
    head: String,
    page: String
})
</script>

<style scoped>
.cards {
    padding: 24px 58px;
    box-shadow: 0px 8px 8px 0px #0000001A;
    display: block;
}

.cards img {
    height: 130px;
    width: 100%;
}

.cards h3 {
    font-family: Open Sans;
    font-size: 20px;
    font-weight: 700;
    line-height: 26px;
    text-align: center;
}

.cards p {
    font-family: Open Sans;
    font-size: 16px;
    font-weight: 400;
    line-height: 24px;
    text-align: center;
}
</style>