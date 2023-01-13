<template>
    <button class="btn-success">{{msg}}</button>
</template>

<script>

export default{
props:{
    msg:{
        type:String,
        required:true,
        default:'Default'
    }
}
}

</script>