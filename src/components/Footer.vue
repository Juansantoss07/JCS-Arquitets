<script>
export default {
    name:"Footer"
}
</script>

<template>
    <footer>
        <p>Powered by <a href="#">Juan Santos</a></p>
    </footer>
</template>

<style scoped>
    footer{
        width: 100%;
        display: flex;
        background: #000;
        color: #fff;
        align-items: center;
        justify-content: center;
        padding: 2rem 2rem;
    }

    a{
        color:#fff;
    }

    a:hover{
        color:#ccc
    }
</style>