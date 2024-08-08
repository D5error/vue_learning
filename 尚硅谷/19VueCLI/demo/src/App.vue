<template>
    <div>
    <School></School>
    <Student></Student>
    </div>
</template>

<script>
    import School from './components/SchoolComponent.vue'
    import Student from './components/StudentComponent.vue'

    export default {
        name: 'App',
        template: `<App></App>`,
        components: {
            School,
            Student
        }
    }
</script>
<!-- 
<style>

</style> -->