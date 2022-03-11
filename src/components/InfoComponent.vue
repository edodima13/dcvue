<template>
    <body>
        <div class="container-info">
            <div class="container">
                <div class="col">
                    <div class="info-wrap">
                        <ul>
                            <li>Dc comics</li>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                </div>
                <div class="col">
                    <div class="info-wrap">
                        <ul>
                            <li>dc</li>
                            <li>Terms Of Use</li>
                            <li>Privacy polici(New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                </div>
                <div class="col">
                    <div class="info-wrap">
                        <ul>
                            <li>sites</li>
                            <li>DC</li>
                            <li>Mad Magazine</li>
                            <li>DC kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>
                <div class="col">
                    <div class="info-wrap">
                        <ul>
                            <li>shop</li>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
        </body>
</template>


<script>

export default {
  name: 'InfoVue',
  
}
</script>

<style lang="scss" scoped>

    body{
        position: relative;
        background-image: url('../img/footer-bg.jpg');
        background-repeat: no-repeat;
        display: flex;
    }
    .container-info{
        width: 1024px;
        padding: 20px 0;
        background-image: url('../img/dc-logo-bg.png');
        background-repeat: no-repeat;
        background-position: center right;
    }
    .container{
        display: flex;
        justify-content: flex-start;
    }
    li{
        list-style: none;
    }
    ul li:first-child{
        font-size: 16;
        text-transform: uppercase;
        color: white;
        font-weight: 700px;
        padding-bottom: 5px;
    }
    ul li{
        font-size: 11px;
        padding-bottom: 3px;
    }
    .col{
        max-width: calc(100% / 9);
        margin: 0;
    }
    .info-wrap{
        padding: 0 5px 3px;
    }

</style>