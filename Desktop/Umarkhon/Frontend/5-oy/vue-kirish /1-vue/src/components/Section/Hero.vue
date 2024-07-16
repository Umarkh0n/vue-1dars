<template>
    <section class="container hero_container flex-center-between"> 
        <div class="hero_words">
            <h2>
            Biznesingizni keyingi bosqichga
olib chiqing
        </h2>
        <p>
            Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar
        </p>
        <Button variant="primary" text="Xizmatlar bilan tanishish"/>
        </div>
        <iframe width="458" height="258" src="https://www.youtube.com/embed/9N3z8RlyXtU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>
    
</template>

<script setup>
import Button from '../Common/Button.vue';

</script>

<style scoped>
.hero_container{
    margin-top: 136px ;
    margin-bottom: 80px;
    
}

.hero_words h2{
    font-family: Open Sans;
font-size: 30px;
font-weight: 700;
line-height: 39px;
text-align: left;

}
.hero_words p{
font-family: Open Sans;
font-size: 16px;
font-weight: 400;
line-height: 24px;
text-align: left;

}
.hero_words {
    max-width: 408px;
}
</style>