<template>
    <form @submit.prevent>
        <div>
        <label>Name</label>
        <input type='text'>
        </div>
           <div>
        <label>Phone</label>
        <input type='tel'>
        </div>
           <div>
        <label>Email</label>
        <input type='email'>
        </div>
        <div>
            <button>Add Friend</button>
        </div>
    </form>
</template>
<script>
export default {
    
}
</script>