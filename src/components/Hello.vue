<template>
    <dev>
        <h1>你好，hello,{{ name }}</h1>
        <el-radio v-model="radio" label="1">备选项1</el-radio>
        <el-radio v-model="radio" label="2">备选项2</el-radio>
    </dev>
</template>

<script>
export default{
    data(){
        return{
            name:"张三",
            radio: "2"
        }
    }
}
</script>