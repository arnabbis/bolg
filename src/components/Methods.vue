<template>
<h1>Company-{{getCompany("Geospoc(Ola)")}}</h1>
<h2>Age-{{getAge().age}}</h2>
</template>

<script>
export default {
    name: "MethodKey",
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
    },
    
}
</script>
