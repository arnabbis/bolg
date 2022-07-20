<template>
<!-- <img src="../assets/geospocimage.png" alt="geospoc"> -->
<h1><u>WELCOME TO MY CODE AND DO SOMETHING INTERESTING</u></h1>
<h2>Email-{{email}} Password-{{password}}</h2>
<h3>Address-{{getAddress("Andal,WestBengal")}}</h3>
</template>

<script>
export default {
    name:"MyCode",
    data(){
        return{
            email:"abc@gmail.com",
            password:"123456",
            place:"westBengal",
            getAddress(a){
                return a
            }
        }
    }
}
</script>


<style scoped>
h1{
    color:olivedrab;
    font-style: inherit;
}
/* template{
    background:yellow;
} */
h2{
    color:cadetblue;
}
</style>