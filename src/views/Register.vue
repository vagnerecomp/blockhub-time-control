<template>
    <div class="register-container">
        <form action="">
            <img src="../assets/block-logo.png" alt="">
            <NameInput/>
            <EmailInput/>
            <PasswordInput/>
            <div class="btn-register">
                <input type="submit" value="Cadastrar">
            </div>
        </form>
    </div>
</template>
<script>
import EmailInput from '../components/EmailInput.vue'
import NameInput from '../components/NameInput.vue'
import PasswordInput from '../components/PasswordInput.vue'
export default{
    name: 'register',
    components:{
        NameInput,
        EmailInput,
        PasswordInput
    }
}
</script>
<style scoped>
    .register-container{
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        background-color: rgba(0,0,0,0.5);
        padding: 50px 15px;
        border-radius: 10px;
    }

    .register-container form{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .register-container form img{
        width: 140px;
        height: 43px;
        margin-bottom: 30px;
    }
    .register-container form .btn-register input{
        width: 200px;
        height: 40px;
        background-color: #fff;
        color: #303134;
        border: none;
        border-radius: 18px;
        position: absolute;
        right: 15px;
    }
    .register-container form .btn-register input:hover{
        border: 3px solid #c9d1d9;
        background-color: rgba(0, 0, 0, 0.7);
        color: #c9d1d9;
    }
</style>