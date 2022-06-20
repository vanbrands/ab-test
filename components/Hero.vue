<template>
    <div>
        <h1>Welcome to this website!</h1>
        <button @click="trackClick">Click Here!!</button>
    </div>
</template>

<script>
export default {
    methods: {
        trackClick(){
            console.log('clicked')
        }
    }
}
</script>