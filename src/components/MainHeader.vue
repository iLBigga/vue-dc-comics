<template>
    <div class="container">
        <nav>
            <figure><img src="../assets/dc-logo.png" alt=""></figure>
            <ul>
                <li><a href="#">characters</a></li>
                <li><a href="#">comics</a></li>
                <li><a href="#">movies</a></li>
                <li><a href="#">tv</a></li>
                <li><a href="#">games</a></li>
                <li><a href="#">collectibles</a></li>
                <li><a href="#">videos</a></li>
                <li><a href="#">fans</a></li>
                <li><a href="#">news</a></li>
                <li><a href="#">shop</a></li>
            </ul>
        </nav>
    </div>
</template>


<script>
export default {
    
}
</script>


<style lang="scss" scoped>

    @import '../style/_variables.scss';

    nav{
        display: flex;
        justify-content: space-between;
        font-weight: 500;

        figure{
            display: flex;
            align-items: center;
        }
    }

    ul {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 30px;
        height: 150px;

        li{
            display: flex;
            align-items: center;
            position: relative;
            text-transform: uppercase;
            cursor: pointer;
            height: 100%;

            &:hover::after{
                content: '';
                position: absolute;
                bottom: 0;
                right: 0;
                left: 0;
                height: 4px;
                background-color: $dc-blue;    
            }

            &:hover{
                color: $dc-blue;    
            }
        }        
    }
</style>