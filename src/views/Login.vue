<template>
    <div>
        <form action="">
            <div class="login-container-out">
                <img src="../assets/block-logo.png" alt="">
                <div class="login-container">
                    <EmailInput/>
                    <PasswordInput/>
                    <SubmitButton/>
                </div>
            </div>
        </form>
        
    </div>
</template>
<script>
import EmailInput from '../components/EmailInput.vue'
import PasswordInput from '../components/PasswordInput.vue'
import SubmitButton from '../components/SubmitButton.vue'
export default {
    name: 'Login',
    components:{
        EmailInput,
        PasswordInput,
        SubmitButton
    }
}
</script>
<style scoped>
    .login-container-out{
        display: flex;
        flex-direction: column;
        align-items: center;
        background-color: rgba(0,0,0,0.5);
        padding: 50px 15px;
        border-radius: 10px;
    }
    .login-container{
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        height: 180px;
        
    }
    form img{
        width: 140px;
        height: 43px;
        margin-bottom: 30px;
    }
</style>
