<template>
    <footer>
        <div class="bagroundColor">
            <Infowords upper="Buyurtma berish"
                down="Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar"
                varian="white" />
            <form class="form">
                <input placeholder="Ismingiz" class="input" type="text">
                <input placeholder="Telefon raqamingiz" class="input" type="number">
                <select class="select">
                    <option class="option" value="">Xizmat turi</option>
                </select>
                <Button class="Btn" text="Buyurtma berish" variant="primary" />

            </form>
        </div>
        <div class="down__baground ">
            <div class="container down_main">
                <div class="max-widthh">
                    <h3>
                        Copyright 2020
                    </h3>
                    <p>
                        Nullam laoreet nec turpis et ultrices. Duis sit amet quam arcu. Nam facilisis lacinia ex, eget
                        sollicitudin massa pellentesque in. Vivamus mattis eros at sem pulvinar tincidunt.
                    </p>
                </div>
                <div>
                    <h3>
                        Sayt sahifalari
                    </h3>
                    <ul>
                        <li>
                            <a href="">
                                Bosh sahifa
                            </a>
                        </li>
                        <li>
                            <a href="">
                                Xizmatlar
                            </a>
                        </li>
                        <li>
                            <a href="">
                                Portfolio
                            </a>
                        </li>
                        <li>
                            <a href="">
                                Jamoa
                            </a>
                        </li>
                        <li>
                            <a href="">
                                Blog
                            </a>
                        </li>
                        <li>
                            <a href="">
                                Kontaktlar
                            </a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h3>
                        Biz internetda
                    </h3>
                    <ul>
                        <li>
                            <a href="">
                                <i><img src="/public/images/telegram.svg" alt=""></i> Telegram
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <i><img src="/public/images/facebook.svg" alt=""></i> Facebook
                            </a>
                        </li>
                        <li>
                            <a href="">
                                <i><img src="/public/images/instagram.svg" alt=""></i> Instagram
                            </a>
                        </li>
                    </ul>
                </div>
            </div>

        </div>
    </footer>
</template>

<script setup>
import Infowords from '../Common/Infowords.vue';
import Button from '../Common/Button.vue';
</script>

<style scoped>
.bagroundColor {
    background: #00BAFC;
    padding: 56px 0;

}

.form {
    margin-top: 8px !important;
    padding: 24px;
    background-color: white;
    max-width: 348px;
    margin: 0 auto;
    border-radius: 5px;

}

.input,
.select,
.option {
    display: block !important;
    width: 90%;
    margin-bottom: 16px;
    padding: 16px;
    outline: none;
    background: #F3F3F3;
    border: none;
    border-radius: 5px;
}

::placeholder {
    color: black;
}

.input,
.select,
.option {
    width: 100%;
}

.Btn {
    text-align: center;
}

.down__baground {
    background-color: black;
    padding-top: 56px;
    padding-bottom: 56px;

}

.down_main {
    display: flex;
    gap: 100px;
    align-items: flex-start;
}

.down_main,
.down_main a {
    color: white;
}

.down_main ul {
    text-align: start;
    padding-left: 0 !important;
}

.down_main li {
    margin-bottom: 8px;
}

.down_main a {
    display: flex;
    align-items: center;
    gap: 8px;
    font-family: Open Sans;
    font-size: 16px;
    font-weight: 400;
    line-height: 24px;
    text-align: left;

}

.down_main h3 {
    font-family: Open Sans;
    font-size: 20px;
    font-weight: 700;
    line-height: 26px;
    text-align: left;
    margin-bottom: 16px;
}

.max-widthh {
    max-width: 320px;
}
</style>