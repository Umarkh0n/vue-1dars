<template>
    <div class="only-words">
        <h3 :class="buttonsStyles()" class="head3">
            {{ upper }}
        </h3>
        <p :class="buttonsStyles()" class="pages">
            {{ down }}
        </p>
    </div>
</template>

<script setup>

const prop = defineProps({
    upper: String,
    down: String,
    varian: String
})

const buttonsStyles = () => {
    switch (prop.varian) {
        case 'white':
            return 'white'
            break
    }
}
</script>

<style scoped>
.white{
    color: white;
}

.only-words {
    max-width: 650px;
    margin: 0 auto;
}

.head3 {
    font-family: Open Sans;
    font-size: 30px;
    font-weight: 700;
    line-height: 39px;
    text-align: center;

}

.pages {
    font-family: Open Sans;
    font-size: 16px;
    font-weight: 400;
    line-height: 24px;
    text-align: center;

}
</style>