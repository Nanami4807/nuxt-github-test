<template>
<div class="background">
    <div class="container animate__animated animate__fadeIn">
        <div class="row text-center">
            <div class="col-md-6">
                <img class="w-75" src="../image/tiku_tizu.png" alt="地図">
            </div>

            <div class="col-md-6">
                <div class="align-items-center">
                    <p><button type="button" class="btn btn-danger mt-3 text-dark w-75" @click="$router.push('/')">中央地区</button></p>
                    <p><button type="button" class="btn btn-danger mt-3 text-dark w-75" @click="$router.push('/')">谷山地区</button></p>
                    <p><button type="button" class="btn btn-danger mt-3 text-dark w-75" @click="$router.push('/')">松元地区</button></p>
                    <p><button type="button" class="btn btn-danger mt-3 text-dark w-75" @click="$router.push('/')">喜入地区</button></p>
                </div>
            </div>
        </div>
    </div>
    <div style="height:300px;">
    </div>
</div>
</template>

<script>
    export default{
        name: 'tiku'
    }
</script>