<template>
  <div>
    <div>
      <Nav>
      </Nav>
    </div>
    <div class="project-container">
       <h1 class="project-title">Projects</h1>
    </div>   
    <div>
      <b-card-group deck>
        <b-card title="Studio Mg" img-src="~/assets/studiomg.jpg" img-alt="Image" img-top tag="article"
          style="max-width: 25rem;" class="mb-2">
          <b-card-text>
            Very minimalistic site made with Wordpress.
          </b-card-text>
          <b-button href="https://studiomg.be/" variant="primary">Check out the site</b-button>
        </b-card>

        <b-card title="CelestialBeauty" img-src="~/assets/celestialbeauty.jpg" img-width="395px" img-height="245px"
          img-alt="Image" img-top tag="article" style="max-width: 25rem;" class="mb-2">
          <b-card-text>
            Beauty salon site with booking capabilities, Made with Angular 9
          </b-card-text>
          <b-button href="https://celestialbeauty.be/" variant="primary">Check out the site</b-button>
        </b-card>

        <b-card title="Card Title" img-src="https://picsum.photos/600/300/?image=25" img-alt="Image" img-top
          tag="article" style="max-width: 25rem;" class="mb-2">
          <b-card-text>
            Some quick example text to build on the card title and make up the bulk of the card's content.
          </b-card-text>
          <b-button href="#" variant="primary">Go somewhere</b-button>
        </b-card>
      </b-card-group>
    </div>

  </div>
</template>

<style>

</style>