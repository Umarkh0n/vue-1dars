<template>
    <div class="work_box container">
        <div class="work_box_left_img">
            <img :src="boxImage" alt="">
            <div>
                <h3>
                    {{ header }}
                </h3>
                <p>
                    {{ pagas }}
                </p>
            </div>
        </div>
        <div class="work_box_right_img">
            <div>
                <h3>
                    {{ headerr }}
                </h3>
                <p>
                    {{ pagass }}
                </p>
            </div>
            <img :src="boxImagee" alt="">
        </div>
    </div>
</template>

<script setup>
defineProps({
    boxImage: String,
    header: String,
    pagas: String,
    boxImagee: String,
    headerr: String,
    pagass: String
})
</script>

<style scoped>
.work_box p, .work_box h3{
    max-width: 430px;
}
.work_box h3{
font-family: Open Sans;
font-size: 20px;
font-weight: 700;
line-height: 26px;
text-align: left;
}

.work_box p{
font-family: Open Sans;
font-size: 16px;
font-weight: 400;
line-height: 24px;
text-align: left;

}

.work_box_left_img, .work_box_right_img{
    display: flex;
    gap: 32px;
    align-items: center;
    justify-content: center;
    margin-bottom: 48px;
}
</style>