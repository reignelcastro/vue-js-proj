<script setup>
    
</script>
<template>
    
        <div class="d-flex align-items-center justify-content-center flex-column vh-100"> 
            <div class="w-40">
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
                    <button class="btn m-1 btn-info"><RouterLink to="signup">Sign up</RouterLink></button>
                </div>
            </div>
        </div>
</template> 
<style scoped>
</style>