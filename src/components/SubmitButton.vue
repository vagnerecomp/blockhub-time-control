<template>
    <div>
        <input type="submit" value="Entrar">
    </div>
</template>
<script>
export default {
    name: 'SubmitButton',
}
</script>
<style scoped>
    input{
        width: 200px;
        height: 40px;
        background-color: #fff;
        color: #303134;
        border: none;
        border-radius: 18px;
        position: absolute;
        right: 35px;    
    }
    input:hover{
        border: 3px solid #c9d1d9;
        background-color: rgba(0, 0, 0, 0.7);
        color: #c9d1d9;
    }
</style>