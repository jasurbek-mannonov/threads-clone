<script setup>
// const client = useSupabaseClient()
// const user = useSupabaseUser()

watchEffect(() => {
    if(user.value){
        return navigateTo('/')
    }
})
</script>

<template>
    <div>

    </div>
</template>
