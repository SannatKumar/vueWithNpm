<template>
    <div>
        <h1>Hello From Home Component</h1>
        <h1>{{data}}</h1>
        <h1>{{msg}}</h1>
        <button @click="hello"> Call Hello Function</button>
    </div>
</template>
<script>


export default{
    name:'Home',
    props:{
        data:String,
        msg: String,
    },
    methods: {
        hello()
        {
            alert("Hello Function Called")
        }
    }        
    }

</script>
