<script>
export default {
  name: "About",
};
</script>

<template>
  <div class="content-about">
    <div class="title">About</div>
    <hr />
    <div class="box-about">
      <div class="text-about">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Quas commodi
          minima explicabo quasi tenetur tempore pariatur accusamus culpa,
          corporis amet sit laudantium repudiandae perspiciatis placeat aperiam
          enim, dicta dolor eligendi. Lorem ipsum dolor sit, amet consectetur
          adipisicing elit. Officia autem dolorem perspiciatis, laboriosam illo
          esse recusandae ipsum deserunt pariatur eligendi, cumque tempora, vel
          accusamus praesentium ducimus porro culpa enim possimus.
        </p>
      </div>
      <div class="cards-about">
        <div class="card">
          <div class="card-img">
            <img src="https://www.w3schools.com/w3images/team2.jpg" alt="" />
          </div>
          <div class="info-about">
            <h1>Jonh Doe</h1>
            <strong>CEO e Founder</strong>
            <p>
              Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse
              sodales pellentesque elementum.
            </p>
            <button class="btn-card">Contact</button>
          </div>
        </div>
        <div class="card">
          <div class="card-img">
            <img src="https://www.w3schools.com/w3images/team1.jpg" alt="" />
          </div>
          <div class="info-about">
            <h1>Jonh Doe</h1>
            <strong>CEO e Founder</strong>
            <p>
              Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse
              sodales pellentesque elementum.
            </p>
            <button class="btn-card">Contact</button>
          </div>
        </div>
        <div class="card">
          <div class="card-img">
            <img src="https://www.w3schools.com/w3images/team3.jpg" alt="" />
          </div>
          <div class="info-about">
            <h1>Jonh Doe</h1>
            <strong>CEO e Founder</strong>
            <p>
              Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse
              sodales pellentesque elementum.
            </p>
            <button class="btn-card">Contact</button>
          </div>
        </div>
        <div class="card">
          <div class="card-img">
            <img src="https://www.w3schools.com/w3images/team4.jpg" alt="" />
          </div>
          <div class="info-about">
            <h1>Jonh Doe</h1>
            <strong>CEO e Founder</strong>
            <p>
              Phasellus eget enim eu lectus faucibus vestibulum. Suspendisse
              sodales pellentesque elementum.
            </p>
            <button class="btn-card">Contact</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.content-about {
  padding: 1rem 2rem;
  width: 100%;
}

.box-about{
    display: flex;
    flex-direction: column;
}

.text-about{
    padding-top: 1rem;
}

.cards-about{
    display:flex;
    width:100%;
    padding-top:3rem;
    justify-content: space-between;
}

.card{
    display: flex;
    flex-direction: column;
    width:24%;
    justify-content: space-around;
    filter: grayscale(75%);
}

.card-img{
    width:100%;
    margin-bottom: 1rem;
}

.card-img img{
    width: 100%;
}

.info-about{
    display: flex;
    flex-direction: column;
}

.info-about h1{
    font-size:24px;
    font-weight: 400;
}

.info-about strong{
    font-size: 15px;
    color: rgb(102, 102, 102);
    margin: 1rem 0;
    font-weight: 100;
}

.btn-card{
    margin-top: 1rem;
    padding: .5rem 0;
    background-color: rgb(209, 209, 209);
    font-size: 15px;
    border: 0;
    cursor: pointer;
}

.btn-card:hover{
    background-color: rgb(160, 160, 160);
}

@media(max-width:780px){
    .cards-about{
        flex-direction: column;
    }

    .card{
        width: 100%;
        padding: 1rem 0;
    }
}
</style>