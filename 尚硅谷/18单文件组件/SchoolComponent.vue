<template>
    <div class="demo">
        <h2>学校名称：{{name}}</h2> 
        <h2>学校地址：{{address}}</h2>
        <hr>
    </div>
</template>

<script>
    export default {
        name: 'School',
        data(){
            return {
                name: 'SYSU',
                address: '广东省深圳市光明区',
            }
        }
    }
    // export default school
</script>

<style>
    .demo{
        background-color: aqua;
    }
</style>