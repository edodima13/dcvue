<template>
    <header>
        <div>
            <img src="../img/dc-logo.png" alt="">
        </div>
        <div>
            <ul class="categories">
                <li>Characters</li>
                <li class="active">Comics</li>
                <li>Movies</li>
                <li>Tv</li>
                <li>Games</li>
                <li>Collectibles</li>
                <li>Videos</li>
                <li>Fans</li>
                <li>News</li>
                <li>Shop</li>
            </ul>
        </div>
      
    </header>
</template>


<script>

export default {
  name: 'HeaderVue',
  
}
</script>

<style lang="scss">
    header{
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    header img{
        display: block;
        width: 80px;
        padding: 10px 0;
    }

    .categories{
        text-transform: uppercase;
        display: flex;
        gap: 15px;
        line-height: 100px;
        
    }
    .categories li{
            text-decoration: none;
            list-style: none;
            font-size: 12px;
            font-weight: 600;
        }
    .active{
        color: #0C7CEC;
        border-bottom: 2px solid #0C7CEC;

    }
</style>