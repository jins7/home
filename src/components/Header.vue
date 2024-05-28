<template>
  <section class="sticky-top">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a href="/">
              <div class="navbar-brand">
                <strong>Kun Wang</strong>
              </div>
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a @click="goToAnchor('#about')" class="nav-link active" aria-current="page" href="#">About</a>
                  </li>
                  <li class="nav-item">
                    <a @click="goToAnchor('#news')" class="nav-link active" aria-current="page" href="#">News</a>
                  </li>
                  <li class="nav-item">
                    <a @click="goToAnchor('#publications')" class="nav-link active" aria-current="page" href="#">Publications</a>
                  </li>
                  <li class="nav-item">
                    <a @click="goToAnchor('#experience')" class="nav-link active" aria-current="page" href="#">Experience</a>
                  </li>
                  <li class="nav-item">
                    <a @click="goToAnchor('#collaborators')" class="nav-link active" aria-current="page" href="#">Collaborators</a>
                  </li>
                  <li class="nav-item">
                    <a @click="goToAnchor('#academic')" class="nav-link active" aria-current="page" href="#">Academic</a>
                  </li>
                  <li class="nav-item">
                    <a @click="goToAnchor('#award')" class="nav-link active" aria-current="page" href="#">Awards</a>
                  </li>
<!--                  <li class="nav-item dropdown">-->
<!--                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"-->
<!--                        data-bs-toggle="dropdown" aria-expanded="false">-->
<!--                        Other-->
<!--                    </a>-->
<!--                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">-->
<!--                        <li>-->
<!--                            <a @click="goToAnchor('#academic')" class="dropdown-item" href="#">Academic Service</a>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                            <a @click="goToAnchor('#Award')" class="dropdown-item" href="#">Award</a>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                            <a @click="goToAnchor('#Work')" class="dropdown-item" href="#">Work Experience</a>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                            <hr class="dropdown-divider">-->
<!--                        </li>-->
<!--                        <li>-->
<!--                            <a @click="goToAnchor('#Interests')" class="dropdown-item" href="#">Interests</a>-->
<!--                        </li>-->
<!--                        <li>-->
<!--                            <a @click="goToAnchor('#Friends')" class="dropdown-item" href="#">Friends</a>-->
<!--                        </li>-->
<!--                    </ul>-->
<!--                  </li>-->
                </ul>
            </div>
        </div>
    </nav>
  </section>
</template>

<script>
export default {
    methods: {
        goToAnchor(selector) {
            document.querySelector(selector).scrollIntoView({
                behavior: "smooth", // 平滑过渡
                block: "start" // 上边框与视窗顶部平齐
            });
        }
    }
}
</script>