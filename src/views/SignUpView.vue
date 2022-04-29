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
                <div class="pss color-black">
                    <button class="btn m-2 btn-info">Save</button>
                    <RouterLink to="login"><button class="btn m-2 btn-danger">Cancel</button></RouterLink>
                </div>
        </div>
    </div>
</template>
<style scoped>

#form-group{
        background-color: #64E986;
        font-weight: bold;
        font-size: 110%;

};
div.pss{    
    color:black;
    font-weight: bold;
};
div.pss :hover{
    background-color: white;
    border-color:black;
    
}; 
</style>