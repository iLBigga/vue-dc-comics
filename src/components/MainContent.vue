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


<style lang="scss" scope>

    @import '../style/_variables.scss';

    main{
        display: flex;
        align-items: center;
        background-color: $main-bg;
        height: 200px;
    }
    
    span {
        color: white;
        font-size: 2rem;
        margin-right: auto;
    }

</style>