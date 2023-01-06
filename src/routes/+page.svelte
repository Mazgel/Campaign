<script>
  import interactionWithPublic from "$lib/images/interaction-with-public.jpg";
</script>

<header>
  <h1 class="title">
    <span class="emphasis red">Manship</span> for
    <span class="blue caps">Head Student</span>
  </h1>
</header>

<section class="campaign-photo">
  <img src={interactionWithPublic} alt="Thomas Manship interacting with the local voting public" />
  <p>POV: Thomas Manship interacting with the local voting public</p>
</section>

<style lang="scss">
  header {
    h1 {
      font-size: 6vw;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    width: 100%;
  }
  .red {
    color: red;
  }
  .blue {
    color: blue;
  }
  .caps {
    text-transform: uppercase;
  }
  .emphasis {
    font-style: italic;
  }

  section {
    display: flex;
    height: 60vh;
    padding-left: 5vw;
    padding-right: 5vw;
    font-size: 3vw;
    p {
      padding-left: 3%;
    }
  }

  .campaign-photo {
    img {
      object-fit: cover;
      height: 100%;
    }
  }
</style>
