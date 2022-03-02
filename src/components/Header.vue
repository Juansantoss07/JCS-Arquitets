<script>
export default {
    name:"Header"
}
</script>

<template>
    <div class="content-header">
        <header>
            <div class="logo">
                <strong>LOGO</strong>
            </div>
            <div class="header-links">
                <div class="link">
                    <a href="#">Projects</a>
                </div>
                <div class="link">
                    <a href="#">About</a>
                </div>
                <div class="link">
                    <a href="#">Contact</a>
                </div>
            </div>
        </header>
    </div>
</template>

<style scoped>
    header{
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding:0.5rem 2rem;
        position: fixed;
        z-index: 100;
        background: #fff;
        border-bottom: 1px solid rgba(27, 27, 27, 0.637);
    }

    .header-links{
        display: flex;
    }

    .header-links a{
        color: #000;
        text-decoration: none;
        text-transform: capitalize;
        font-weight: 400;
        font-size: 18px;
        letter-spacing: .1rem;
    }

    .link{
        margin: 0 1rem;
        padding: 0.5rem 1rem;
    }

    .link:hover{
        background:rgb(185, 185, 185)
    }

</style>