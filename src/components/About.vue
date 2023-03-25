<template>
  <div class="h-100 h-mob">
    <h1>{{ msg }}</h1>
    <div
      class="m-0 w-100 z-n1 position-absolute z-n1 mob-vid"
      style="
        height: 50% !important;
        overflow-y: hidden;
        background-color: black;
      "
    >
      <video
        src="../assets/pexels-kelly-lacy-6595364.mp4"
        loop="loop"
        autoplay="autoplay"
        class="js-hero-video z-n1 opacity-50"
      ></video>
    </div>
    <div class="w-100 p-5 h-50 row" style="">
      <div
        class="w-50 text-end text-light col about-info"
        data-aos="slide-left"
        data-aos-duration="500"
      >
        <h3 class="text-light mt-5">Spend smarter with Spendesk</h3>
        <p class="opacity-75">
          Imagine a software that helps you make smarter spending decisions and
          contributes to real growth, instead of putting more work on your
          plate. That’s Spendesk. We replace the complicated and bureaucratic
          process of managing company money with one complete spend management
          solution. Spendesk increases team productivity and collaboration,
          provides businesses with visibility and control, and frees up valuable
          time so that the finance team (and everyone in the company) can focus
          on strategic topics to grow your business.
        </p>
      </div>
      <h1
        class="col text-center text-light my-5"
        style="font-size: 100px ;color: #CAA77F !important;"
        data-aos="slide-right"
        data-aos-duration="500"
      >
        About us
      </h1>
    </div>
  </div>
  <div class="container h-100 w-100 text-center py-5">
    <h2 class="my-5">This is the new spend playbook.</h2>
    <div class="row gap-3 m-5">
      <div
        class="card column-md-5 hvr-float-shadow"
        style="width: 18rem"
        data-aos="slide-up"
        data-aos-duration="500"
        data-aos-delay="100"
      >
        <img
          src="https://img.freepik.com/free-vector/people-analyzing-growth-charts_23-2148866843.jpg?w=996&t=st=1679647265~exp=1679647865~hmac=2b14be9505c1510c37ec60f7107c9aaaeeee405dc0d208043c96987d68c7a187"
          class="card-img-top"
          alt="..."
        />
        <div class="card-body">
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
        </div>
      </div>
      <div
        class="card column-md-5 hvr-float-shadow"
        style="width: 18rem"
        data-aos="slide-up"
        data-aos-duration="500"
        data-aos-delay="200"
      >
        <img
          src="https://img.freepik.com/free-vector/strategic-consulting-concept-illustration_114360-8994.jpg?w=740&t=st=1679647339~exp=1679647939~hmac=92180bf5de5da7b0965f06275bc7737a4042f5f619e418d46a8a2d539b95cce5"
          class="card-img-top"
          alt="..."
        />
        <div class="card-body">
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
        </div>
      </div>
      <div
        class="card column-md-5 hvr-float-shadow"
        style="width: 18rem"
        data-aos="slide-up"
        data-aos-duration="500"
        data-aos-delay="300"
      >
        <img
          src="https://img.freepik.com/free-vector/goal-achievement-teamwork-business-concept-career-growth-cooperation-development-project_107791-29.jpg?1&w=740&t=st=1679647360~exp=1679647960~hmac=72d58abfbc93580987f1fc2f356539c3553e91a8f36e751b1e4ab1e1fe77ad78"
          class="card-img-top"
          alt="..."
        />
        <div class="card-body">
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
        </div>
      </div>
      <div
        class="card column-md-5 hvr-float-shadow"
        style="width: 18rem"
        data-aos="slide-up"
        data-aos-duration="500"
        data-aos-delay="400"
      >
        <img
          src="https://img.freepik.com/free-vector/male-team-illustration_23-2150201042.jpg?w=996&t=st=1679647399~exp=1679647999~hmac=709751e17db8c47c57b9182a30064112614a1dc5f7a45229a41843a3674a5aa1"
          class="card-img-top"
          alt="..."
        />
        <div class="card-body">
          <p class="card-text">
            Some quick example text to build on the card title and make up the
            bulk of the card's content.
          </p>
        </div>
      </div>
    </div>
  </div>
  <div
    class="container w-100"
    style="
      background-image: linear-gradient(
        109.5deg,
        rgba(229, 233, 177, 1) 11.2%,
        rgba(223, 205, 187, 1) 100.2%
      );
    "
  >
    <h3 class="text-center py-5">Frequently asked questions</h3>
    <div
      class="accordion accordion-flush w-100 px-4 pb-5"
      id="accordionFlushExample"
    >
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#flush-collapseOne"
            aria-expanded="false"
            aria-controls="flush-collapseOne"
          >
            When do i begin to use product after purchase?
          </button>
        </h2>
        <div
          id="flush-collapseOne"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionFlushExample"
        >
          <div class="accordion-body">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Officiis
            cum omnis quas soluta commodi, facilis vitae dignissimos rem
            doloribus neque non necessitatibus? Saepe doloremque aperiam
            adipisci praesentium expedita consequatur reprehenderit.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#flush-collapseTwo"
            aria-expanded="false"
            aria-controls="flush-collapseTwo"
          >
            Which other websites can i buy?
          </button>
        </h2>
        <div
          id="flush-collapseTwo"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionFlushExample"
        >
          <div class="accordion-body">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla,
            dolorem voluptatibus! Obcaecati quod fuga dicta, architecto,
            quisquam deleniti facilis minus repudiandae libero aspernatur
            ducimus delectus maxime voluptates esse nam vel. Lorem ipsum dolor
            sit amet, consectetur adipisicing elit. Voluptates reiciendis quod
            exercitationem blanditiis, placeat, excepturi ipsa quo veritatis
            doloribus impedit tenetur maiores voluptatibus itaque, libero dicta
            mollitia accusantium laboriosam ea!
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#flush-collapseThree"
            aria-expanded="false"
            aria-controls="flush-collapseThree"
          >
            I got sscammed, what do i do?
          </button>
        </h2>
        <div
          id="flush-collapseThree"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionFlushExample"
        >
          <div class="accordion-body">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nobis eos
            eum ullam, accusamus consequuntur sit? Consectetur necessitatibus
            neque expedita repudiandae tempora dolores rerum. Autem earum hic ab
            nesciunt corrupti molestias.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#flush-collapseFour"
            aria-expanded="false"
            aria-controls="flush-collapseFour"
          >
            Found a bug, who should i contact?
          </button>
        </h2>
        <div
          id="flush-collapseFour"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionFlushExample"
        >
          <div class="accordion-body">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Saepe
            quidem debitis accusantium at et iste vero esse, dolorum voluptatum
            dolorem officiis nihil non quo eaque! Cupiditate impedit vero amet
            recusandae?.
          </div>
        </div>
      </div>
    </div>
  </div>
  <h3 class="text-center">Meet the team</h3>
  <div class="row w-100 gap-3 m-5 mobile">
    <div
      class="card pt-4 mb-3 hvr-bob border-light column-md-5"
      style="
        max-width: 400px;
        max-height: 100px;
        background-image: linear-gradient(
          83.2deg,
          rgba(150, 93, 233, 1) 10.8%,
          rgba(99, 88, 238, 1) 94.3%
        );
      "
    >
      <div class="row g-0 m-2">
        <div
          class="col-md-5"
          data-aos="slide-up"
          data-aos-duration="500"
          data-aos-delay="100"
        >
          <img
            src="https://as1.ftcdn.net/v2/jpg/02/99/04/20/1000_F_299042079_vGBD7wIlSeNl7vOevWHiL93G4koMM967.jpg"
            class="img-fluid rounded-start"
            alt="..."
            style="width: 100%; height: 100%"
          />
        </div>
        <div
          class="col-md-7"
          data-aos="slide-up"
          data-aos-duration="500"
          data-aos-delay="200"
        >
          <div class="card-body bg-dark text-light">
            <h5 class="card-title">Daniel Udofa</h5>
            <p class="text-danger">Founder</p>
            <p class="card-text row">
              <i class="bi bi-facebook col hvr-bounce-in"></i>
              <i class="bi bi-linkedin col hvr-bounce-in"></i>
              <i class="bi-twitter col hvr-bounce-in"></i>
              <i class="bi-github col hvr-bounce-in"></i>
              <i class="bi-envelope-at col hvr-bounce-in"></i>
            </p>
          </div>
        </div>
      </div>
    </div>
    <div
      class="card pt-4 mb-3 hvr-bob border-light column-md-5"
      style="
        max-width: 400px;
        max-height: 100px;
        background-image: linear-gradient(
          358.4deg,
          rgba(249, 151, 119, 1) -2.1%,
          rgba(98, 58, 162, 1) 90%
        );
      "
    >
      <div
        class="row g-0 m-2"
        data-aos="slide-up"
        data-aos-duration="500"
        data-aos-delay="200"
      >
        <div class="col-md-5">
          <img
            src="https://as1.ftcdn.net/v2/jpg/04/74/20/88/1000_F_474208856_EoL6uq3YlFiDpd8iB6EQOs88uXEFJdcy.jpg"
            class="img-fluid rounded-start"
            alt="..."
            style="width: 100%; height: 100%"
          />
        </div>
        <div class="col-md-7">
          <div class="card-body bg-dark text-light">
            <h5 class="card-title">Daniel Udofa</h5>
            <p class="text-danger">Founder</p>
            <p class="card-text row">
              <i class="bi bi-facebook col hvr-bounce-in"></i>
              <i class="bi bi-linkedin col hvr-bounce-in"></i>
              <i class="bi-twitter col hvr-bounce-in"></i>
              <i class="bi-github col hvr-bounce-in"></i>
              <i class="bi-envelope-at col hvr-bounce-in"></i>
            </p>
          </div>
        </div>
      </div>
    </div>
    <div
      class="card pt-4 mb-3 hvr-bob border-light column-md-5"
      style="
        max-width: 400px;
        max-height: 100px;
        background-image: linear-gradient(
          68.3deg,
          rgba(245, 177, 97, 1) 0.4%,
          rgba(236, 54, 110, 1) 100.2%
        );
      "
    >
      <div
        class="row g-0 m-2"
        data-aos="slide-up"
        data-aos-duration="500"
        data-aos-delay="300"
      >
        <div class="col-md-5">
          <img
            src="https://as2.ftcdn.net/v2/jpg/04/95/15/79/1000_F_495157971_zIhzjfx3yG1AsgYOTQS9Z6VHAsN0OJSI.jpg"
            class="img-fluid rounded-start"
            alt="..."
            style="width: 100%; height: 100%"
          />
        </div>
        <div class="col-md-7">
          <div class="card-body bg-dark text-light">
            <h5 class="card-title">Daniel Udofa</h5>
            <p class="text-danger">Founder</p>
            <p class="card-text row">
              <i class="bi bi-facebook col hvr-bounce-in"></i>
              <i class="bi bi-linkedin col hvr-bounce-in"></i>
              <i class="bi-twitter col hvr-bounce-in"></i>
              <i class="bi-github col hvr-bounce-in"></i>
              <i class="bi-envelope-at col hvr-bounce-in"></i>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@media (min-width: 350px) and (max-width: 950px) {
  .mobile {
    height: 79rem;
    // gap: 18rem !important;
    padding: 1rem !important;
    margin-bottom: 3rem !important;
    margin: 0 !important;
  }
  .mob-vid {
    height: 1rem !important;
  }
  .about-info {
    display: none;
  }
  .h-mob {
    height: 20rem !important;
    margin-right: 5rem !important;
    h1 {
      font-size: 3rem !important;
    }
  }
}
.z-n1 {
  z-index: -1;
}
video {
  width: 100%;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
