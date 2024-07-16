<template>
    <section class="work">
        <Infowords upper="Biz qanday ishlaymiz?" down="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar"/>
        <WorkBox boxImage="/images//work-1.svg" header="Talablarni aniqlab chiqamiz" pagas="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis" boxImagee="/images//work-2.svg" headerr="Bir necha yechimlarni taklif qilamiz" pagass="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
        <WorkBox boxImage="/images//work-3.svg" header="Loyiha uchun vaqt belgilaymiz" pagas="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis" boxImagee="/images//work-4.svg" headerr="A'lo sifat bilan bajarib topshiramiz" pagass="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
        <WorkBox boxImage="/images//work-5.svg" header="Qo'llab-quvvatlab boramiz" pagas="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis"/>
        <Button class="last_btn" text="Buyurtma berish" variant="primary"/>
    </section>
</template>

<script setup>
import Infowords from '../Common/Infowords.vue';
import WorkBox from '../Common/WorkBox.vue';
import Button from '../Common/Button.vue';


</script>

<style scoped>
.work{
    margin-top: 56px;
    margin-bottom: 56px;
}
.last_btn{
    text-align: center;
}
</style>