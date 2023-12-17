<script>
</script>
<template>
    <div class="container">
        <img src="../../public/assets/img/MasterStudy_logo.svg" alt="#">
        <p>CATEGORY</p>
        <input type="text" placeholder="Search courses">
        <div></div>
        <p>Become an Instructor</p>
        <p>For Enterprise</p>
        <p>Log in</p>
        <button id="sign_up">SIGN UP</button>
    </div>
    <div>
        <font-awesome-icon :icon="['fas', 'music']" />
        <font-awesome-icon :icon="['fas', 'star']" />
        <font-awesome-icon :icon="['far', 'heart']" />
    </div>
</template>
<style scoped>
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    width: 90%;
    margin: auto;
}

#sign_up {
    background-color: blue;
    color: white;
    border: none;
    padding: 1rem 30px;
    border-radius: 25px;
}
</style>
