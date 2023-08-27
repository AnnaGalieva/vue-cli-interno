<template>
    <div class="box-content">
        <header class="header center">
            <nav class="header__left">
                <router-link to="/" class="header__left_logo footer__interno_logo" href="#">
                    <svg xmlns="http://www.w3.org/2000/svg" width="34" height="34" viewBox="0 0 34 34" fill="none">
                        <path
                            d="M0 34.0003H13.4588V24.499C13.4588 22.4853 15.0898 20.8543 17.1035 20.8543C19.1172 20.8543 20.7482 22.4853 20.7482 24.499V34.0003H33.9975V0C15.2211 0 0 15.2211 0 34.0003Z"
                            fill="#CDA274" />
                    </svg></router-link>
                <router-link to="/" class="header__left_brand footer__interno_brand" href="index.html">Interno</router-link>
            </nav>
            <nav class="header__right">
                <router-link to="/" class="header__right_text" href="index.html">Home </router-link>
                <router-link to="/Project" class="header__right_text" href="#">Project</router-link>
                <router-link to="/Blog" class="header__right_text" href="blog.html">Blog </router-link>
            </nav>
        </header>
    </div>
</template>
<script>
export default {
    name: 'Head',
};
</script>