<template>
<h1>Company-{{getCompany("Geospoc(Ola)")}}</h1>
<input type="text" placeholder="E-MAIL" v-model="email"/>
<input type="password" placeholder="PASSWORD" v-model="password"/>
<button v-on:click="getData()" type="button">GET DATA</button>
<h2>Age-{{getAge().age}}</h2>
</template>

<script>
export default {
    name: "MethodKey",

    data(){

        return{
            email:null,
            password:null,
        }
    },
    methods: {

        getCompany(company) {
            return company
        },
        getAge(){
        return {
            dob:"14/03/2000",
            age:22,
        }
    },
     getData(){
            return console.warn("email: ",this.email,"password: ",this.password)
        },
    },
    
}
</script>
