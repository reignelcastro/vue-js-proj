<script setup>
</script>

<template>
<div>
    <RouterLink to="/"><Button class="btn btn-secondary">Back</Button></RouterLink>
</div>
    <div class="d-flex align-items-center justify-content-center flex-column vh-100">
        <h1>Note Application</h1>
        <div class="w-50">
            <div class="form-group">
                <label for="">Title</label>
                <input type="text" class="form-control"/>
            </div>
            <div class="form-group">
                <label for="">Content</label>
                <textarea name="" id="" cols="30" rows="5" class="form-control"></textarea>
            </div>
            <button class="btn btn-primary mt-1">Save</button>
        </div>
    </div>
</template>
<style scoped>
    h1{
        color: red;
    }
</style>