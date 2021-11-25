<template>
    <div>
        <h1 class="vueStyle"> Class and Style Bindings</h1>
        <h1 v-bind:style = "{color:colorName}"> Style Bindings</h1>
        <h1 v-bind:class = "{display: show, vueStyle: show}">Class bindings</h1>
        <h1 v-bind:style = "{color:colorName}"> Class With Objects</h1>
        <h1 v-bind:class = "['display', 'vueStyle']">Class with Array</h1>
        <h1 v-bind:class = "[d, v]">Class with variable assignment</h1>
    </div>
</template>

<script>
export default{
    name: 'BindClassAndStyle',
    data(){
        return{
            message:"Hi",
            colorName: 'skyblue',
            show: true,
            d: 'display',
            v: 'vueStyle'
        }
    }

}
</script>
<style lang="css" scoped>
.vueStyle{
    color: 'orange';
}
.display{
    background-color: peru;
    padding: 5px;
}
</style>

