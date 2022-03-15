<template>
    <div class="container-content">
        <div class="content-empty">
            <img :src="srcThumb" alt="">
            <div>
                <h6>{{title}}</h6>
            </div>
        </div>
        
    </div>
</template>
<script>

export default{
    props:{
        srcThumb:{
            type: String,
            required: true
        },
        title:{
            type: String,
            required: true
        }
    }
}
</script>
<style >
h6{
    color: white;
    text-transform: uppercase;
    text-align: center;
}


</style>
