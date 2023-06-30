<script>
export default{
    data(){
        return{
            message:"Hello"
        }
    }
}
</script>

<template>
    <div>
        <h1 style="white-space: pre-line;">{{ message }}</h1>
        <textarea type="text" v-model="message" />
    </div>
</template>