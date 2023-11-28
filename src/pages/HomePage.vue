<template>
    <div class="box-content">
        <main class="main">
            <section class="top__content center">
                <div class="top__content_img">
                    <img class="top__content_image" src="@/assets/img/top__content_img.svg" alt="top__content_img">
                </div>
                <div class="top__content_info">
                    <h1 class="top__content_info_title">Let Your Home Be Unique</h1>
                    <h2 class="top__content_info_subtitle">There are many variations of the passages of lorem Ipsum
                        fromavailable, majority.</h2>
                    <router-link to="/NotFound">
                        <div class="top__content_info_button">
                            <button class="top__content_info_btn">Get Started&nbsp;<svg xmlns="http://www.w3.org/2000/svg"
                                    width="19" height="17" viewBox="0 0 19 17" fill="none">
                                    <path d="M2 8.43542L15.7232 8.29857M10.6182 1.91138L17.1412 8.43436L10.4868 15.0887"
                                        stroke="#CDA274" stroke-width="2" stroke-linecap="square" stroke-linejoin="round" />
                                </svg></button>
                        </div>
                    </router-link>
                </div>
            </section>
            <section class="projects center">
                <div class="projects__info">
                    <p class="projects__info_header">Follow Our Projects</p>
                    <p class="projects__info_text">It is a long established fact that a reader will be distracted by the of
                        readable content of page lookings at its layouts points.</p>
                </div>
                <div class="projects__all">
                    <div v-for="projectCard in  projectCards " :key="projectCard.id" class="projects__all_item">
                        <img :src=projectCard.img alt="" class="projects__all_item_img1">
                        <div class="projects__all_item_content">
                            <div class="projects__all_item_content_text">
                                <p class="projects__all_item_content_text_1">{{ projectCard.header }}</p>
                                <nav class="projects__all_item_content_breadcrumb">
                                    <ul class="projects__all_item_content_breadcrumb_ul">
                                        <li class="projects__all_item_content_breadcrumb_li">
                                            <a class="projects__all_item_content_breadcrumb_link" href="">{{
                                                projectCard.link1 }}</a>
                                        </li>
                                        <li class="projects__all_item_content_breadcrumb_li">
                                            <a class="projects__all_item_content_breadcrumb_link" href="">{{
                                                projectCard.link2 }}</a>
                                        </li>
                                    </ul>
                                </nav>
                            </div>
                            <div class="projects__all_item_content_button">
                                <router-link to="/Project" class="projects__all_item_content_btn"><svg
                                        xmlns="http://www.w3.org/2000/svg" width="70" height="70" viewBox="0 0 70 70"
                                        fill="none">
                                        <circle cx="35" cy="35" r="35" fill="#F4F0EC" />
                                        <path d="M32 44L40 35L32 26" stroke="#292F36" stroke-width="2"
                                            stroke-linecap="round" stroke-linejoin="round" />
                                    </svg></router-link>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="results center">
                <div class="results__item results__item1">
                    <p class="results__item_number">12</p>
                    <p class="results__item_text">Years Of Experiance</p>
                </div>
                <div class="results__item_line results__item_line1"></div>

                <div class="results__item results__item2">
                    <p class="results__item_number">85</p>
                    <p class="results__item_text">Success Project</p>

                </div>
                <div class="results__item_line results__item_line2"></div>


                <div class="results__item results__item3">
                    <p class="results__item_number">15</p>
                    <p class="results__item_text">Active Project</p>

                </div>
                <div class="results__item_line results__item_line3"></div>


                <div class="results__item">
                    <p class="results__item_number">95</p>
                    <p class="results__item_text">Happy CUstomers</p>
                </div>
            </section>
            <section class="news center">
                <div class="news__info">
                    <p class="news__info_header">Articles & News</p>
                    <p class="news__info_text">It is a long established fact that a reader will be distracted by the of
                        readable
                        content of a page when lookings at its layouts the points of using.</p>
                </div>
                <div class="news__all">
                    <div v-for="newsCard in newsCards" :key="newsCard.id" class="news__all_item">
                        <img :src=newsCard.img alt="" class="news__all_item_img">
                        <a class="news__all_item_text" href="blog_details.html">{{ newsCard.name }}</a>
                        <div class="news__all_item_content">
                            <p class="news__all_item_content_text">{{ newsCard.header }}</p>
                            <div class="news__all_item_content_contentmin">
                                <p class="news__all_item_content_texting">{{ newsCard.date }} </p>
                                <div class="news__all_item_content_button">
                                    <router-link to="/Blog" class="news__all_item_content_btn"><svg
                                            xmlns="http://www.w3.org/2000/svg" width="52" height="53" viewBox="0 0 52 53"
                                            fill="none">
                                            <circle cx="26" cy="26.267" r="26" fill="#F4F0EC" />
                                            <path d="M23.7714 32.9527L29.7143 26.267L23.7714 19.5813" stroke="#292F36"
                                                stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                                        </svg></router-link>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </main>
    </div>
</template>
<script>
export default {
    name: 'HomePage',
    data() {
        return {
            projectCards: [
                {
                    img: require("@/assets/img/projects__all_item_img1.png"),
                    header: 'Modern Kitchan',
                    link1: 'Decor',
                    link2: 'Artchitecture'
                }, {
                    img: require("@/assets/img/projects__all_item_img2.png"),
                    header: 'Modern Kitchan',
                    link1: 'Decor',
                    link2: 'Artchitecture'
                }, {
                    img: require("@/assets/img/projects__all_item_img3.png"),
                    header: 'Modern Kitchan',
                    link1: 'Decor',
                    link2: 'Artchitecture'
                },
                {
                    img: require("@/assets/img/projects__all_item_img4.png"),
                    header: 'Modern Kitchan',
                    link1: 'Decor',
                    link2: 'Artchitecture'
                },
            ],
            newsCards: [
                {
                    img: require("@/assets/img/news1.svg"),
                    name: 'Living Design',
                    header: 'Let’s Get Solution For Building Construction Work',
                    date: '26 December, 2022',
                },
                {
                    img: require("@/assets/img/news2.svg"),
                    name: 'Kitchan Design',
                    header: 'Low Cost Latest Invented Interior Designing Ideas.',
                    date: '22 December, 2022',
                },
                {
                    img: require("@/assets/img/news3.svg"),
                    name: 'Interior Design',
                    header: 'Best For Any Office & Business Interior Solution',
                    date: '25 December, 2022',
                },
            ],
        };
    },
}
</script>
<style lang="scss" scoped></style>