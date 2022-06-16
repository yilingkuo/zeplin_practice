<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>
<template>
<div class="h-screen flex justify-center items-end">
    <div id="content-wrapper" class="h-screen  flex flex-col ">
        <div class="head-container z-30 flex mt-28">
            
            <img class="col-1 ml-16" src="../assets/廠商 logo.png"/>
            <div class="flex-1 mr-4">
                <p class="text-4xl my-4 font-bold">流亞科技股份有限公司</p>
                <p class="text-xl font-thin">Logic Art Automation Co., Ltd</p>
            </div>
        </div>
        <div class="z-40">
            <img class="screen col-1 ml-16" src="../assets/廠商首頁圖上傳圖.png"/>
            <!-- <p>screen puts here?</p> -->

        </div>

        <div class="z-50 mt-auto flex justify-center">
            <img class="product-list cursor-pointer" src="../assets/products list green.png"/>
        </div>
    </div>

    
    <img class="z-0 Stall-image-green" src="../assets/Stall image green.png"/>
    

<!-- <p class="text-2xl">{{ msg }}</p> -->
</div>

</template>
<style scoped>
.screen{
    /* margin-top: 460px; */
    /* margin-left: 50px;
    margin-bottom: 220px; */
    width: 650px;
  height: 400px;
  margin: 178.3px 0px 46.5px 0px;
  object-fit: contain;

}

.head-container{
    width: 700px;
}
img.Stall-image-green {
    position: fixed;
    width: 1428px;
    height: 966.2px;
    margin: 0.2px 0 1px;
    padding: 57.6px 48.2px 39.8px 51.3px;
    object-fit: contain;
}
.product-list {
    width: 357.1px;
    height: 87.6px;
    margin-bottom: 85px;
    object-fit: contain;
}
</style>