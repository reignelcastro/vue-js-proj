<script setup>
    
</script>
<template>
    
        <div class="d-flex align-items-center justify-content-center flex-column vh-100"> 
            <div class="w-25">
                <h2>Login Page</h2>
                <div class="unm">
                    <label for="username">Username: </label>
                    <input type="text" class="form-control">
                </div>
                <div class="pss">
                    <label for="password">Password: </label>
                    <input type="password" class="form-control">
                </div>
                <div class="btns mt-2">
                    <button class="btn m-1 btn-primary">Login</button>
                    <RouterLink to="signup"><button class="btn m-1 btn-info">Sign up</button></RouterLink>
                </div>
            </div>
        </div>
</template> 
<style scoped>
div.d-flex{
    background-color:rgb(21, 49, 126);
    color:black;
    font-weight:bold;
    font-size: 110%;
};
button{
    font-family:monospace;
    color:white;
};
</style>