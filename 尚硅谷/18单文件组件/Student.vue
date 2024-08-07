<template>
    <div class="demo">
        <h2>学生姓名：{{name}}</h2> 
        <h2>学生年龄：{{age}}</h2>
        <hr>
    </div>
</template>

<script>
    export default {
        name: 'Student',
        data(){
            return {
                name: 'D5error',
                age: 20,
            }
        }
    }
</script>