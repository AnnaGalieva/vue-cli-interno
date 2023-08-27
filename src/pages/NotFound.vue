<template>
    <div class="box-content">
        <main class="main">
            <section class="not-found center">
                <div class="not-found__page">
                    <div class="not-found__page_about">
                        <h1 class="not-found__page_about_heading">404</h1>
                        <h3 class="not-found__page_about_text">We are sorry, but the page
                            you requested was not found</h3>
                        <router-link to="/" class="not-found__page_about_btn">Back To Home
                            <svg xmlns="http://www.w3.org/2000/svg" width="18" height="17" viewBox="0 0 18 17" fill="none">
                                <path d="M1.85938 8.43542L15.5826 8.29857M10.4776 1.91138L17.0005 8.43436L10.3461 15.0887"
                                    stroke="#CDA274" stroke-width="2" stroke-linecap="square" stroke-linejoin="round" />
                            </svg></router-link>
                    </div>
                    <div class="not-found__page_img"><img src="@/assets/img/notfound.png" alt="404"></div>
                </div>
            </section>
        </main>
    </div>
</template>

<script>
export default {
    name: 'NotFound',

    data() {
        return {

        };
    },

    methods: {

    },
};
</script>

<style lang="scss" scoped></style>