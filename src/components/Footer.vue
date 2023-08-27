<template>
    <div class="box-content">
        <footer class="footer">
            <section class="footer__page center">
                <div class="footer__interno">
                    <router-link to="/" class="footer__interno_logo"><svg xmlns="http://www.w3.org/2000/svg" width="35"
                            height="34" viewBox="0 0 35 34" fill="none">
                            <path
                                d="M0.5 34.0003H13.9588V24.499C13.9588 22.4853 15.5898 20.8543 17.6035 20.8543C19.6172 20.8543 21.2482 22.4853 21.2482 24.499V34.0003H34.4975V0C15.7211 0 0.5 15.2211 0.5 34.0003Z"
                                fill="#CDA274" />
                        </svg></router-link>
                    <router-link to="/" class="footer__interno_brand">Interno</router-link>
                    <p class="footer__interno_text">It is a long established fact that a reader will be distracted lookings.
                    </p>
                    <a href="#"><img class="footer__interno_twiter" src="@/assets/img/twiter.svg" alt=""></a>
                    <a href="#"><img class="footer__interno_in" src="@/assets/img/in.svg" alt=""></a>
                </div>
                <div class="footer__pages">
                    <p class="footer__pages_heading">Pages</p>
                    <router-link to="/" class="footer__pages_text">Home</router-link>
                    <router-link to="/Project" class="footer__pages_text">Project</router-link>
                    <router-link to="/Blog" class="footer__pages_text">Blog</router-link>

                </div>
                <div class="footer__contact">
                    <p class="footer__contact_heading">Contact</p>
                    <p class="footer__contact_address">55 East Birchwood Ave. Brooklyn, New York 11201 </p>
                    <p class="footer__contact_email">contact@interno.com</p>
                    <p class="footer__contact_phone">(123) 456 - 7890</p>
                </div>
            </section>
        </footer>
    </div>
</template>
<script>
export default {
    name: 'Footer',
};
</script>