<template>
    <div>
        <h1 class="vueStyle"> Class and Style Bindings</h1>
        <h1 v-bind:style = "{color:'skyblue'}"> Style Bindings</h1>
        <h1 v-bind:class = "{display: show}">Class bindings</h1>
    </div>
</template>

<script>
export default{
    name: 'BindClassAndStyle',
    data(){
        return{
            message:"Hi"
        }
    }

}
</script>
<style lang="css" scoped>
.vueStyle{
    color: orange;
}
</style>

