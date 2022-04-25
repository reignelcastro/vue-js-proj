<script setup>

</script>
<template>
    <div class="d-flex align-items-center justify-content-center flex-column vh-100" id="form-group">
        <h2>Sign Up</h2>
        <div class="form-group w-25">
                <div class="fn">
                    <label for="name">Fullname: </label>
                    <input type="text" class="form-control">
                </div>
                <div class="sid">
                    <label for="id">School ID: </label>
                    <input type="text" class="form-control">
                </div>
                <div class="unm">
                    <label for="username">Username: </label>
                    <input type="text" class="form-control">
                </div>
                <div class="pss">
                    <label for="password">Password: </label>
                    <input type="password" class="form-control">
                </div>
                <div class="pss">
                    
                    <button class="btn m-1 btn-info">Save</button>
                    <button class="btn m-1 btn-danger">Cancel</button>
                </div>
        </div>
    </div>
</template>
<style scoped>

#form-group{
        background-color: aqua;

};
</style>