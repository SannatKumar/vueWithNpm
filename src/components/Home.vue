<template>
    <div>
        <h1>For loop in Vue js</h1>
        <table border="2 px">
            <tr>
                <td>Id</td>
                <td>Name</td>
                <td>Email</td>
            </tr>
            <tr v-for="user in users" :key="user.id">
                <td>{{user.id}}</td>
                <td>{{user.name}}</td>
                <td>{{user.email}}</td>
            </tr>
        </table>
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
            users:[
                {id:1, name: "peter", email:"peter@test.com"},
                {id:2, name: "sam", email:"sam@test.com"},
                {id:3, name: "agroman", email:"agroman@test.com"},
                {id:4, name: "chubby", email:"chubby@test.com"},
                {id:5, name: "maya", email:"maya@test.com"},
                {id:6, name: "honey", email:"honey@test.com"},
                {id:7, name: "petteri", email:"petteri@test.com"},

            ]
        }
    },
}        
    

</script>
