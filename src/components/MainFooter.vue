<template>
    <footer>
        <div class="footer-nav">
            <div class="container">
                <ul>
                    <li><a href="#"><img src="../assets/buy-comics-digital-comics.png" alt=""><span>digital comics</span></a></li>
                    <li><a href="#"><img src="../assets/buy-comics-merchandise.png" alt=""><span>dc merchandise</span></a></li>
                    <li><a href="#"><img src="../assets/buy-comics-subscriptions.png" alt=""><span>subscription</span></a></li>
                    <li><a href="#"><img src="../assets/buy-comics-shop-locator.png" alt=""><span>comic locator</span></a></li>
                    <li><a href="#"><img src="../assets/buy-dc-power-visa.svg" alt=""><span>sc power visa</span></a></li>
                </ul>
            </div>
        </div> 
        <div class="footer-list">
            <div class="container">
                <div class="main-list">
                    <div>
                        <ul>
                            <h4>dc comics</h4>
                                <li><a href="#">Characters</a></li>
                                <li><a href="#">Comics</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">TV</a></li>
                                <li><a href="#">Games</a></li>
                                <li><a href="#">Videos</a></li>
                                <li><a href="#">News</a></li>
                            </ul>
                            <ul>
                                <h4>shop</h4>
                                <li><a href="#">Shop DC</a></li>
                                <li><a href="#">hop DC Collectibles</a>S</li>
                            </ul>
                    </div>
                    <div>
                            <ul>
                            <h4>dc</h4>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy(New)</a></li>
                            <li><a href="#">Ad Choises</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                        <div>
                            <ul>
                                <h4>sites</h4>
                                <li><a href="#">DC</a></li>
                                <li><a href="#">MAD Magazine</a></li>
                                <li><a href="#">DC Kids</a></li>
                                <li><a href="#">DC Universe</a></li>
                                <li><a href="#">DC Power Visa</a></li>
                            </ul>
                        </div>
                    </div>
                <div class="logo-list">
                </div>
            </div>
        </div>
        <div class="footer-contacts">
            <div class="container">
                <div>
                     <a class="sign-up-button" href="#">sign-up now!</a>
                </div>
                   <div>
                    <ul class="footer-social-link">
                        <h3>follow us</h3>
                        <li><a href="#"><img src="../assets/footer-facebook.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-twitter.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-youtube.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-periscope.png" alt=""></a></li>
                        <li><a href="#"><img src="../assets/footer-periscope.png" alt=""></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>


<script>
export default {
    
}
</script>


<style lang="scss" scoped>

    @import '../style/_variables.scss';

    footer{
        .footer-nav{
            background-color: $dc-blue;

            .container{
                height: 250px;
                display: flex;
                justify-content: space-between;     
            }

            ul{
            display: flex;
            flex-grow: 1;
            justify-content: space-between;
            align-items: center;
            }

            img {
            width: 45px;
            }

            a{
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1rem;
            text-transform: uppercase;
            color: white;
            }
        }

        .footer-list {
            background-image: url('../assets/footer-bg.jpg');
            background-size: cover;

                .container {
                    display: flex;
                    align-items: center;
                    justify-content: space-between;
                    gap: 3rem;

                        .main-list{
                            display: flex;
                            flex-basis: 60%;
                            gap: 100px;
                        }

                        h4{
                            font-size: 1.7rem;
                            text-transform: uppercase;
                            color: white;
                            padding: 1rem 0;
                        }

                        li {
                            line-height: 1.8rem;
                            font-size: 1rem;
                            color: $footer-text-color;
                        }

                        .logo-list {
                            height: 500px;
                            flex-basis: 40%;
                            background-image: url('../assets/dc-logo-bg.png');
                            background-repeat: no-repeat;
                            background-position: center;
                        }
                }
        }

        .footer-contacts {
            background-color: $footer-contacts-bg;
            padding: 2.72rem;

            .container {
                display: flex;
                justify-content: space-between;
                align-items: center; 
            }

            .sign-up-button {
                text-transform: uppercase;
                color: white;
                padding: 1rem;
                border: 2px solid $dc-blue;
            }

            .footer-social-link {
                display: flex;
                align-items: center;
                gap: 1.5rem;
                
                    
                h3{
                    color: $dc-blue;
                    text-transform: uppercase;
                }
            }
        }
    }  
</style>