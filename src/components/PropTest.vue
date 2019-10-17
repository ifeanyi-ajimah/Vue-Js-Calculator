<template>
    <div>
        <h1>nwanne boys </h1>
        {{ msg }}
        {{ propB }}
        {{ propC }}
        {{ propD }}
    </div>
</template>

<script>
export default {
    
    props:{
        msg : String,
        propB: String,
        propC: String,
        propD : Number,
    },

    // props:['msg','propB','propC','propD'] 
}
</script>


<style scoped>

</style>




