<template>
  <footer>
    <div class="container-social-media">
      <div class="social-media">
        <div class="card-social">
          <a
						aria-label=""
            target="_blank"
            class="url-social"
            href="https://www.instagram.com/cristhiandev.pe/"
          >
            <img
              src="@/assets/images/social/instagram.svg"
              class="icon-social"
              alt="instagram"
            />
          </a>
        </div>

        <div class="card-social">
          <a
            target="_blank"
            class="url-social"
            href="https://www.facebook.com/cristhiandevpe"
          >
            <img
              src="@/assets/images/social/facebook.svg"
              class="icon-social"
              alt="facebook"
            />
          </a>
        </div>

        <div class="card-social">
          <a
            target="_blank"
            class="url-social"
            href="https://www.linkedin.com/in/cristhian-smith-ze%C3%B1a-mas-cristhiandev-6324a3103/"
          >
            <img
              src="@/assets/images/social/linkedin.svg"
              class="icon-social"
              alt="linkedin"
            />
          </a>
        </div>

        <div class="card-social">
          <a
            target="_blank"
            class="url-social"
            href="https://twitter.com/zena_cristian"
          >
            <img
              src="@/assets/images/social/twitter.svg"
              class="icon-social"
              alt="twitter"
            />
          </a>
        </div>

        <div class="card-social">
          <a
            target="_blank"
            class="url-social"
            href="https://github.com/crismith"
          >
            <img
              src="@/assets/images/social/github.svg"
              class="icon-social"
              alt="github"
            />
          </a>
        </div>
      </div>
    </div>
    <div class="data-footer">
      <h6 class="description-one">
        Desarrollado con mucho 💚 por
        <br>
        &copy; Cristhian Zeña Mas 
      </h6>
    </div>
  </footer>
</template>

<script>
export default {
  computed: {
    year() {
      let dateYear = new Date();
      var year = dateYear.getFullYear();
      return year;
    }
  }
};
</script>

