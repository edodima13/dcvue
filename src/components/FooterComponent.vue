<template>
    <footer>
        <div class="container">
            <div class="button">
                <button>
                    shop now
                </button>
            </div>
            <div class="follow">
                <h3>
                    follow us
                </h3>
                <div class="social-icons">
                    <img src="../img/footer-facebook.png" alt="">
                    <img src="../img/footer-periscope.png" alt="">
                    <img src="../img/footer-pinterest.png" alt="">
                    <img src="../img/footer-twitter.png" alt="">
                    <img src="../img/footer-youtube.png" alt="">
                </div>
            </div>
        </div>        
    </footer>
</template>


<script>

export default {
  name: 'FooterVue',
  
}
</script>

<style lang="scss" scoped>


footer{
    background-color: #242424;  
    padding: 20px 0; 
}

.container{
    max-width: 1024px;
    display: flex;
    align-items: center;
}

button{
    background-color: transparent;
    border: 2px solid #2050A1;
    padding: 5px;
    color: white;
    text-transform: uppercase;
}

.button{
    margin: 0;
}

.follow{
    display: flex;
    margin-right: 0;
}

.follow h3{
    text-transform: uppercase;
    color: #2050A1;
    align-self: center;
    padding-right: 10px;
}

.social-icons{
    margin: 0;
    display: flex;
    gap: 10px;
}

img{
    width: 30px;
}


</style>