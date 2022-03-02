<script>
export default {
  name: "Project",
};
</script>

<template>
  <div class="content-projects">
    <div class="title">Projects</div>
    <hr />
    <div class="galery-projects">
      <div class="project-img-box">
        <div class="project-img">
            <strong>Summer House</strong>
          <img src="https://www.w3schools.com/w3images/house5.jpg" alt="" />
        </div>
        <div class="project-img">
            <strong>Brick House</strong>
          <img src="https://www.w3schools.com/w3images/house2.jpg" alt="" />
        </div>
        <div class="project-img">
            <strong>Renovated</strong>
          <img src="https://www.w3schools.com/w3images/house3.jpg" alt="" />
        </div>
        <div class="project-img">
            <strong>Barn House</strong>
          <img src="https://www.w3schools.com/w3images/house4.jpg" alt="" />
        </div>
      </div>
      <div class="project-img-box">
        <div class="project-img">
            <strong>Summer House</strong>
          <img src="https://www.w3schools.com/w3images/house2.jpg" alt="" />
        </div>
        <div class="project-img">
            <strong>Brick House</strong>
          <img src="https://www.w3schools.com/w3images/house5.jpg" alt="" />
        </div>
        <div class="project-img">
            <strong>Renovated</strong>
          <img src="https://www.w3schools.com/w3images/house4.jpg" alt="" />
        </div>
        <div class="project-img">
            <strong>Barn House</strong>
          <img src="https://www.w3schools.com/w3images/house3.jpg" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
    .content-projects{
        padding: 2rem;
    }

    .galery-projects{
        width:100%;
        display: flex;
        flex-direction: column;
    }

    .project-img-box{
        display: flex;
        width: 100%;
        padding-top: 1rem;
        justify-content: space-between;
    }

    .project-img{
        width: 24%;
    }

    .project-img img{
        width: 100%;
    }

    .project-img strong{
        position: absolute;
        padding: 0.5rem 1rem;
        background-color: #000;
        color: #fff;
        font-weight: 100;
    }

    @media(max-width:780px){
        .project-img-box{
            flex-direction: column;
        }

        .project-img{
            width: 100%;
        }
    }

</style>