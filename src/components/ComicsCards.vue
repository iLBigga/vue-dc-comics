<template>
    <div class="grid">
        <article class="card" v-for="(comic, i) in comics" :key="i">
            <img :src="comic.thumb" :alt="comic.series">
            <div>{{comic.series}}</div>
        </article>
    </div>
</template>

<script>

export default {
    props: {
        comics: Array,
    }
}


</script>

<style lang="scss" scoped>
    .grid{
        display: grid;
        padding: 4rem 0;
        grid-template-columns: repeat(6, 1fr);
    }

    .card {
        padding: 1rem;
        text-align: center;

            div{
                padding: 1rem;
                text-transform: uppercase;
            }
    }
</style>