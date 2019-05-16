<template>
    <div>
        <header></header>
        <body>
            <el-input v-model="userNaem" placeholder="userName"></el-input>
            <el-input v-model="password" placeholder="Password"></el-input>
            <el-button></el-button>
        </body>
        
    </div>
</template>

<script>
export default {

    data () {
        return {
            userName: '',
            password: '',
           
        }
    },
    methods:{
        
    }

}
</script>

<style>

</style>
