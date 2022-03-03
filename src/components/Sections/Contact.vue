<script>
export default {
    name:"Contact"
}
</script>

<template>
    <div class="content-contact">
        <div class="title">
            Contact
        </div>
        <hr>
        <div class="box-contact">
            <div class="text">
                <p>
                    Lets get in touch and talk about your next project.
                </p>
            </div>
            <div class="inputs">
                <input type="text" placeholder="Name">
                <input type="email" placeholder="Email">
                <input type="text" placeholder="Subject">
                <input type="text" placeholder="Comment">
            </div>
            <div class="btn-contact">
                <input type="submit" value="Send Message">
            </div>
        </div>
    </div>
</template>

<style scoped>
    .content-contact{
        padding:1rem 2rem;
        width: 100%;
    }

    .text p{
        margin: 1rem 0;
    }
    .box-contact{
        display: flex;
        flex-direction: column;
        padding: 1rem 0;
        width: 100%;
    }

    .inputs{
        display: flex;
        flex-direction: column;
    }

    .inputs input[type=email], input[type=text]{
        padding: .5rem;
        width: 100%;
        font-size:15px;
        margin-bottom: .5rem;
    }

    .btn-contact input[type=submit]{
        margin-top: 1.5rem;
        padding: 0.5rem 1rem;
        background-color:#000;
        color:#fff;
        text-transform: uppercase;
        border: none;
        cursor:pointer;
        font-size: 15px;
    }

    .btn-contact input[type=submit]:hover{
        background-color: rgb(209, 209, 209);
        color:#000;
    }
</style>