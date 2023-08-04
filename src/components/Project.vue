<template>
    <div class="box-content">
        <main class="main">
            <section class="project center">
                <div class="project__info">
                    <div class="project__info__heading">
                        <h1 class="project__info__heading_text">Our Project</h1>
                        <nav class="project__info__heading_breadcrumb">
                            <ul class="project__info__heading_breadcrumb_ul">
                                <li class="project__info__heading_breadcrumb_li">
                                    <a class="project__info__heading_breadcrumb_link" href="">Home</a>
                                </li>
                                <li class="project__info__heading_breadcrumb_li">
                                    <a class="project__info__heading_breadcrumb_link" href="">Project</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </div>
            </section>
            <section class="categories center">
                <div class="categories__tags">
                    <div class="categories__tags_button">
                        <button class="categories__tags_btn">
                            <h1 class="categories__tags_btn_text"></h1>
                        </button>
                    </div>
                </div>
                <div class="categories__all">
                    <div class="categories__all_image">
                        <img class="categories__all_img" src="" alt="img">
                    </div>
                    <div class="categories__all_content">
                        <div class="categories__all_content_text">
                            <p class="categories__all_content_texting">Modern Kitchan</p>
                            <nav class="categories__all_content_breadcrumb">
                                <ul class="categories__all_content_breadcrumb_ul">
                                    <li class="categories__all_content_breadcrumb_li">
                                        <a class="categories__all_content_breadcrumb_link" href="">Decor</a>
                                    </li>
                                    <li class="categories__all_content_breadcrumb_li">
                                        <a class="categories__all_content_breadcrumb_link" href="">Artchitecture</a>
                                    </li>
                                </ul>
                            </nav>
                        </div>
                        <div class="categories__all_content_button">
                            <button class="categories__all_content_btn"><svg xmlns="http://www.w3.org/2000/svg" width="70"
                                    height="70" viewBox="0 0 70 70" fill="none">
                                    <circle cx="35" cy="35" r="35" fill="#F4F0EC" />
                                    <path d="M32 44L40 35L32 26" stroke="#292F36" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                </svg></button>
                        </div>
                    </div>

                </div>
            </section>
        </main>

    </div>
</template>

<script>
export default {
    name: 'Project',

    data() {
        return {

        };
    },

    methods: {

    },
};
</script>

<style lang="scss" scoped></style>