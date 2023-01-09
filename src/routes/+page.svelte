<script>
  import interactionWithPublic from "$lib/images/interaction-with-public.jpg";
</script>

<header>
  <h1 class="title">
    <span class="green emphasis">Manship</span> <span class="purple">for</span>
    <span class="caps"><span class="blue">Head</span> <span class="yellow">Student</span></span>
  </h1>
</header>

<main>
  <section>
    <div class="image-wrapper">
      <img
        src={interactionWithPublic}
        alt="Thomas Manship interacting with the local voting public"
      />
    </div>
    <div class="text-wrapper">
      <p>POV: Thomas Manship interacting with the local voting public</p>
    </div>
  </section>

  <section>
    <div class="image-wrapper">
      <img
        src={interactionWithPublic}
        alt="Thomas Manship interacting with the local voting public"
      />
    </div>
    <div class="text-wrapper">
      <p>POV: Thomas Manship interacting with the local voting public</p>
    </div>
  </section>

  <section>
    <div class="image-wrapper">
      <img
        src={interactionWithPublic}
        alt="Thomas Manship interacting with the local voting public"
      />
    </div>
    <div class="text-wrapper">
      <p>POV: Thomas Manship interacting with the local voting public</p>
    </div>
  </section>

  <section>
    <div class="image-wrapper">
      <img
        src={interactionWithPublic}
        alt="Thomas Manship interacting with the local voting public"
      />
    </div>
    <div class="text-wrapper">
      <p>POV: Thomas Manship interacting with the local voting public</p>
    </div>
  </section>

  <section>
    <div class="image-wrapper">
      <img
        src={interactionWithPublic}
        alt="Thomas Manship interacting with the local voting public"
      />
    </div>
    <div class="text-wrapper">
      <p>POV: Thomas Manship interacting with the local voting public</p>
    </div>
  </section>
</main>

<style lang="scss">
  $color-green: #3ea535;
  $color-purple: #6f4692;
  $color-blue: #41a3db;
  $color-yellow: #dfc500;

  header {
    h1 {
      font-size: clamp(3em, 6vw, 8em);
      margin: 0;
      padding: 0;
      text-align: center;
    }
  }

  section {
    display: flex;
    justify-content: center;
    align-items: center;

    padding-top: 2vh;
    padding-bottom: 2vh;
    padding-left: 5vw;
    padding-right: 5vw;

    gap: 2em;

    height: clamp(30em, 60vh, 80vw);

    .image-wrapper {
      height: 100%;

      img {
        width: 100%;
        height: 100%;

        object-fit: scale-down;
      }
    }

    .text-wrapper {
      font-size: 3em;
      max-width: 60%;
    }
  }

  section:nth-child(odd) {
    flex-direction: row;
  }

  section:nth-child(even) {
    flex-direction: row-reverse;
  }

  main {
    section:first-child {
      border-top-left-radius: 3vw;
      border-top-right-radius: 3vw;
    }

    section:last-child {
      border-bottom-left-radius: 3vw;
      border-bottom-right-radius: 3vw;
    }
  }

  @media screen and (max-width: 60em) {
    section {
      height: auto;
      padding: 2em;
      gap: 0;
      .text-wrapper {
        font-size: 1.7em;
        max-width: 100%;
        text-align: center;
      }
    }

    section:nth-child(odd) {
      flex-direction: column;
    }

    section:nth-child(even) {
      flex-direction: column;
    }

    main {
      section:first-child {
        border-radius: 0;
      }

      section:last-child {
        border-radius: 0;
      }
    }
  }

  section:nth-child(4n-3) {
    background-color: lighten($color-green, 40%);
  }
  section:nth-child(4n-2) {
    background-color: lighten($color-purple, 40%);
  }
  section:nth-child(4n-1) {
    background-color: lighten($color-blue, 40%);
  }
  section:nth-child(4n-0) {
    background-color: lighten($color-yellow, 40%);
  }

  .green {
    color: $color-green;
  }
  .purple {
    color: $color-purple;
  }
  .blue {
    color: $color-blue;
  }
  .yellow {
    color: $color-yellow;
  }

  .caps {
    text-transform: uppercase;
  }
  .emphasis {
    font-style: italic;
  }
</style>
