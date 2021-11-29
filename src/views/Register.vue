<template>
    <div class="register-container">
        <NameInput/>
        <EmailInput/>
        <PasswordInput/>
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