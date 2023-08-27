<template>
    <div class="box-content">
        <main class="main">
            <section class="poject-details center">
            </section>
            <section class="poject-details__content center">
                <div class="poject-details__content_about" v-for="item in data" :key="item">
                    <h1 class="poject-details__content_title"> {{ item.title }}</h1>
                    <p class="poject-details__content_text1"> {{ item.text1 }}</p>
                    <p class="poject-details__content_text2"> {{ item.text2 }}</p>
                </div>
                <Swipers />
            </section>

        </main>

    </div>
</template>

<script>
import { mapState } from 'vuex';
import Swipers from '../components/Swipers.vue'

export default {
    name: 'ProjectDetails',
    components:{Swipers},

    data() {
        return {

        };
    },
    computed: {
        ...mapState(['data'])
    },
    methods: {

    },
};
</script>

<style lang="scss" scoped></style>