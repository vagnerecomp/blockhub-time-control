<template>
  <div class="form-control">
                <div class="txt-group">
                    <input id="txtForMail" name="txtForMail" placeholder="maratonas" type="password">
                    <label for="txtForMail">Senha</label>
                    <br>
                    <span class= "hidden">Mensagem de erro</span>
                </div>
            </div>
</template>

<script>
export default {
    name: 'PasswordInput'


}
</script>

<style scoped>
        .txt-group{
    position: relative;
    display:inline-block;
    margin-bottom: 15px;
    }
    .txt-group input{
        width: 452px;
        height: 60px;
        background: transparent;
        border: 2px solid #c9d1d9;
        box-sizing: border-box;
        border-radius: 10px;

        /* font styles */
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 22px;

        padding-left: 16px;
        padding-top: 26px;
        color: #fff;
    }
    .txt-group input::placeholder{
        color: transparent;
    }
    .txt-group label{
        position: absolute;
        left: 16px;
        top: 19px;

        /* font styles */
        font-style: normal;
        font-weight: normal;
        font-size: 16px;
        line-height: 22px;
        color: #c9d1d9;
        transition: all 0.1s;
    }
    .txt-group input:focus + label,
    .txt-group input:not(:placeholder-shown) + label{
        top: 7px;
        font-size: 13px;
    }
    .txt-group span{
        font-style: normal;
        font-weight: 400;
        font-size: 15px;
        line-height: 18px;
        color: #FFA00A;
        padding-left: 2px;
        display: none;
    }
</style>