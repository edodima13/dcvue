<template>
    <body>
        <div class="container-merch">
            <li>
                <img src="../img/buy-comics-digital-comics.png" alt="">
                <h5>digital comics</h5>
            </li>
            <li>
                <img src="../img/buy-comics-merchandise.png" alt="">
                <h5>dc merchandise</h5>
            </li>
            <li>
                <img src="../img/buy-comics-shop-locator.png" alt="">
                <h5>subscription</h5>
            </li>
            <li>
                <img src="../img/buy-comics-subscriptions.png" alt="">
                <h5>comic shop locator</h5>
            </li>
            <li>
                <img src="../img/buy-dc-power-visa.svg" alt="">
                <h5>dc power visa</h5>
            </li>
        </div>
        
        <div>
            
        </div>
      
    </body>
</template>


<script>

export default {
  name: 'MerchVue',
  
}
</script>

<style lang="scss" scoped>

    body{
        background-color: #0C7CEC;
    }
    .container-merch{
        max-width: 1024px;
        display: flex;
        gap: 20px;
        justify-content: center;
    }
    li{
        display: flex;
        align-items: center;
        gap: 5px;
        color: white;
        text-transform: uppercase;
        font-size: 13px;
        white-space: nowrap;
    }
    li img{
        max-width: 35px;
        object-fit: cover;
        padding: 20px 0;
    }

</style>