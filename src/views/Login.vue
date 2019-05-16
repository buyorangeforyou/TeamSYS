<template>
    <div>
        <header>{{user.userName}}{{pass}}</header>
        <body></body>
        
    </div>
</template>

<script>
export default {

    data () {
        return {
            user:{
                userName: 'lcl',

            },
            pass: "123456",
        }
    },
    methods:{
        
    }

}
</script>

<style>

</style>
