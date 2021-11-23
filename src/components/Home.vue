<template>
    <div>
        <h1 v-if="show">Conditional Rendering in Vue js</h1>
        <h1 v-else>Else Side</h1>
        <button v-on:click = "display">Toogle</button>
        

    </div>
</template>
<script>


export default{
    name:'Home',
    props:{
        data:String,
        msg: String,
    },data(){
        return{
            show:false
        }
    },
    methods:{
        display()
        {
            this.show=!this.show
        }
    }
}        
    

</script>
