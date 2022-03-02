<script>
export default {
    name:"Home"
}
</script>

<template>
    <section>
        <strong>JCS</strong>
        <h1>Arquitets</h1>
    </section>
</template>

<style scoped>
    section{
        height: 100vh;
        background-image: url("https://images.pexels.com/photos/262347/pexels-photo-262347.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260");
        background-position: center;
        background-size: cover;
        display: flex;
        align-items: center;
        justify-content: center;
        width: 100%;
    }

    strong{
        font-size: 64px;
        background: rgba(0, 0, 0, 0.671);
        color: #fff;
        padding: 0 1rem;
    }

    h1{
        font-size: 64px;
        color: #fff;
        margin-left: 1rem;
    }

    @media(max-width:540px){
        section{
            flex-direction: column;
        }

        h1{
            margin:0;
        }
    }
</style>