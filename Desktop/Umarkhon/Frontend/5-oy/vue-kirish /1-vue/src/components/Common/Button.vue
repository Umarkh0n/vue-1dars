<template>
    <div>
        <button :class="buttonsStyles()" class="buttons">
            {{ text }}
        </button>
    </div>
</template>

<script setup>
import { defineProps } from 'vue'
const props = defineProps({
    text: String,
    variant: String
})

const buttonsStyles = () => {
    switch (props.variant) {
        case 'primary':
            return 'primary'
            break
        case 'red':
            return 'red'
            break
    }
}
</script>

<style scoped>
.buttons {
    padding: 8px 16px;
    border: none;
    cursor: pointer;
    
}

.primary {
    background: #00BAFC;
    color: white;
    border-radius: 5px;
    font-weight: 700;
    font-size: 15px;
    font-family: Open Sans;
}

.red {
    background: red;
    color: white;
    border-radius: 8px;
    font-weight: bold;
    font-size: 15px;
}
</style>