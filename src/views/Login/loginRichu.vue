<template>
<<<<<<< HEAD
    <div>
        <h1>我是登录目录</h1>
=======
    <div class="login">
        <div class="box">
            <div class="left">
                <img src="../../assets/images/hoshino.png"></img>
            </div>
            <div class="right">
                <h4>登 录</h4>
                <el-form :model="logininfos" :rules="rules" ref="loginforms">
                    <el-form-item prop="username">
                        <el-input class="acc" type="text" placeholder="输入用户名" :prefix-icon="User"
                            v-model="logininfos.username">
                        </el-input>
                    </el-form-item>
                    <el-form-item prop="password">
                        <el-input class="acc" type="password" placeholder="密码" :prefix-icon="Lock"
                            v-model="logininfos.password" :show-password="true">
                        </el-input>
                    </el-form-item>
                    <input class="submit" value="Login" @click="submit">
                </el-form>
            </div>
        </div>
>>>>>>> 56a8778e9e5317507b7d344cda36908b812a3b4c
    </div>
</template>

<script setup lang="ts">

</script>

<<<<<<< HEAD
<style scoped></style>
=======
<style scoped lang="less">
.login {
    width: 100%;
    height: 100vh;
    background-color: rgb(144, 129, 241);
}

::selection {
    color: #fff;
    background-color: rgb(144, 129, 241);
}

.box {
    display: flex;
    overflow: hidden;
    width: 90rem;
    height: 55rem;
    background-color: rgba(255, 255, 255, 60%);
    border-radius: 1.5rem;
    margin: 0 auto;
    box-shadow: 0 0 1rem 0.2rem rgb(0 0 0 / 10%);
}

.box .left {
    position: relative;
    width: 35%;
    height: 90%;
    background-color: skyblue;

    img {
        margin: auto auto;
        height: 90%;
        object-fit: fill;
        margin-top: 16px;

    }
}

.box .left::before {
    content: '';
    position: absolute;
    width: 100%;
    height: 100%;
    background-size: cover;
    opacity: 80%;
}

.box .right {
    display: flex;
    width: 65%;
    flex-direction: column;
    align-items: center;
}

.box .right h4 {
    color: rgb(144, 129, 241);
    font-size: 3rem;
    margin-top: 5rem;
}

el-form {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.acc {
    outline: none;
    width: 800px;
    height: 5rem;
    font-size: 1.6rem;
    margin-top: 5rem;
    padding: 1rem 0 0 1.6rem;
    border: none;
    border-bottom: 1px solid rgb(144, 129, 241);
    color: rgb(144, 129, 241);
    background-color: rgba(0, 0, 0, 0);
}

.acc:focus {
    outline: none;
    color: rgb(144, 129, 241);
    padding: 1rem 0 0 1.6rem;
}

.right .submit {
    width: 60%;
    height: 5rem;
    color: #f6f6f6;
    background-image: linear-gradient(120deg, #e0c3fc 0%, #8ec5fc 100%);
    font-size: 1.4rem;
    border: none;
    border-radius: 0.5rem;
    margin: 6rem 0 0 50%;
    transform: translateX(-50%);
    text-align: center;
    line-height: 5rem;
}

.right .submit:hover {
    box-shadow: 0 0 2rem -0.5rem rgb(0 0 0 / 15%);
}

.right .fn {
    display: flex;
    justify-content: space-between;
    margin-top: 1rem;
    width: 70%;
}

.right .fn a {
    text-decoration: none;
    font-size: 1.5rem;
    margin-top: 5rem;
    padding: 1rem 2rem;
    color: #666;
}

.right .fn a:hover {
    color: rgb(144, 129, 241);
}
</style>
>>>>>>> 56a8778e9e5317507b7d344cda36908b812a3b4c
