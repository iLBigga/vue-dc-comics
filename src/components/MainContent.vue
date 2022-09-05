<template>
    <main class="main-bg">
        <div class="container">
            <span> --> Content goes here  </span>
        </div>
    </main>
</template>


<script>
export default {
    
}
</script>


<style lang="scss" scoped>

    @import '../style/_variables.scss';

    main{
        display: flex;
        align-items: center;
        background-color: $main-bg;
        height: 250px;
    }
    
    span {
        color: white;
        font-size: 2rem;
        margin-right: auto;
    }

</style>