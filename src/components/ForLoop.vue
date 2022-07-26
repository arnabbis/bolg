<template>
  <div>
    <h1>{{data}} {{msg}}</h1>
    <table border="2px" align="center">
        <tr>
            <td>Name</td>
            <td>Place</td>
            <td>Email</td>
        </tr>
        <tr v-for="user in users" :key="user">
            <td>{{user.name}}</td>
            <td>{{user.place}}</td>
            <td>{{user.email}}</td>
        </tr>
    </table>
  </div>
</template>

<script>
export default {
    name:"ForLoop",
    props:{
        data:String,
        msg:String,
    },
    data(){
        return{
            users:[
                {name:"arnab",place:"westbengal",email:"abc2gmail.com"},
                {name:"hayat",place:"uttarpradesh",email:"xyz2gmail.com"},
                {name:"vikash",place:"uttarakhand",email:"uvw2gmail.com"},
            ],
        }
    }
}
</script>

<style  scoped>
table{
    border-color: blue;
}
</style>>
