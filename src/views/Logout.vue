<template>
    
</template>
<script>
export default {
    created() {
        this.$store.dispatch('destroyToken');
    },
};
</script>
