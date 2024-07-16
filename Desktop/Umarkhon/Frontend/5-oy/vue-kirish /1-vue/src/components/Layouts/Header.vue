<template>
    <header class="header">
        <div class="container flex-center-between !py-2">
            <Logo />
            <ul class="list flex-center-between">
                <li class="list__item">
                    <RouterLink to="/">
                        Bosh sahifa
                    </RouterLink>
                </li>
                <li class="list__item">
                    <RouterLink to="/Xizmatlar">
                        Xizmatlar
                    </RouterLink>
                </li>
                <li class="list__item">
                    <RouterLink to="/Portfolio">
                        Portfolio
                    </RouterLink>
                </li>
                <li class="list__item">
                    <RouterLink to="/Jamoa">
                        Jamoa
                    </RouterLink>
                </li>
                <li class="list__item">
                    <RouterLink to="/Blog">
                        Blog
                    </RouterLink>
                </li>
                <li class="list__item">
                    <RouterLink to="/Kontaktlar">
                        Kontaktlar
                    </RouterLink>
                </li>
                <li class="list__item">
                    <a href="tel:+998990052600">
                        <Button variant="primary" text="+998 90 921 37 11" />
                    </a>
                </li>
            </ul>

        </div>
    </header>
</template>

<script setup>
import Button from '../Common/Button.vue';
import Logo from '../Common/Logo.vue';

</script>

<style scoped>
.list {
    list-style: none !important;
}

.list__item {
    margin-left: 32px;
}

.list__item a  {
    color: black;
    font-family: sans-serif;
    font-weight: 500;
}

.header{
    box-shadow: 0px 4px 20px 0px #0000001A;
    position: fixed;
    top: 0px;
    width: 100%;
    z-index: 50;
    background-color: white;
}
</style>