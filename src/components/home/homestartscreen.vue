<template>
    <div class="container-fluid">
        <div class="row py-5 align-items-center">
            <div class="col-md-4 text-center">
                <img class="profileimg" :src="maindata1.imgUrl" alt="">
            </div>
            <div class="col-md-8">
                <h1>{{maindata1.name}}</h1>
                     <p>Student at IGDTUW || Community Manager at InCampus Ltd ||
                    <br>|| GigIndia and NEO Campus Ambassador || DSC member ||</p>
            </div>
        </div>
    </div>
</template>
<script>
import maindata from '@/assets/data/main.json'
    export default {
        name:'HomeScreen',
        data:()=>({
            maindata1:maindata
        })
    }
</script>

<style>
    .profileimg{
        border-radius: 50%;
        width: 80%;
        margin-left: auto;
        margin-right: auto;
    }
</style>