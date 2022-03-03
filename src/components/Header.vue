<script>
export default {
    name:"Header",

    methods:{
        menuon(){
            document.getElementById('nav').style.display = 'flex';
            document.getElementById('on').style.display = 'none';
        },
        menuoff(){
            document.getElementById('nav').style.display = 'none';
            document.getElementById('on').style.display = 'flex';
        }
    }
}
</script>

<template>
    <div class="content-header">
        <header>
            <div class="logo">
                <strong>LOGO</strong>
            </div>
            <button class="btn-mobile" id="on" @click="menuon"><i class="bi bi-list"></i></button>
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
        <div class="nav-mobile" id="nav">
            <button class="btn-mobile" id="off" @click="menuoff"><i class="bi bi-x-circle"></i></button>
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

    .btn-mobile{
        display: none;
        border: 0;
        background: transparent;
        font-size: 24px;
    }

    #off{
        margin-bottom: 1rem;
    }
     .nav-mobile{
        position: fixed;
        z-index: 100;
        background: rgb(255, 255, 255);
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        width: 100%;
        height: 50%;
        display: none;
        justify-content: space-evenly;
    }

    .nav-mobile a{
        font-size: 28px;
        color: #000;
        text-decoration: none;
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

    @media(max-width:780px){
        .btn-mobile{
            display: block;
        }

        .header-links{
            display: none;
        }
    }
</style>