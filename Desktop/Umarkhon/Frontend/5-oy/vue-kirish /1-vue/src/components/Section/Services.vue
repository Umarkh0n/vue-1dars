<template>
    <section class="services">
        <Infowords upper="Xizmatlar"
            down="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar" />
        <div class="box_cards container">
            <Cards image="/images/website-illustration.svg" head="Vebsayt tuzish" page="lorem ipsum" />
            <Cards image="/images/cards-second.svg" head="Telegram bot" page="lorem ipsum" />
            <Cards image="/images/cards-third.svg" head="SMM" page="lorem ipsum" />
            <Cards image="/images/cards-four.svg" head="Grafik dizayn" page="lorem ipsum" />
            <Cards image="/images/cards-five.svg" head="CRM tizimlar" page="lorem ipsum" />
        </div>
        <div class="buttons_link">
            <Button text="Buyurtma berish" variant="primary" />
            <a href="#">Xizmatlar sahifasiga o’tish</a>
        </div>
    </section>
</template>

<script setup>
import Cards from '../Common/Cards.vue';
import Infowords from '../Common/Infowords.vue';
import Button from '../Common/Button.vue';


</script>

<style scoped>
.services {
    margin-top: 38px;
    margin-bottom: 82px;
}

.box_cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    row-gap: 70px;
    column-gap: 48px;
}

.buttons_link {
    display: flex;
    justify-content: center;
    margin-top: 48px;
    gap: 16px;
    align-items: center;
}

.buttons_link a {
    color: #00BAFC;
    font-family: Open Sans;
    font-size: 16px;
    font-weight: 400;
    line-height: 24px;
    text-align: center;
    text-decoration: underline !important;
}
</style>
