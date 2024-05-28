<template>
  <Header />
  <Introduction/>
  <About />
  <News />
  <Publications />
  <Experience />
  <Collaborators />
  <Academic />
  <Award />
  <Footer />
</template>

<script>
import Header from './components/Header.vue'
import Introduction from './components/Introduction.vue'
import About from './components/About.vue'
import Publications from './components/Publications.vue';
import Experience from './components/Experience.vue';
import Academic from './components/Academic.vue';
import Award from './components/Award.vue';
import Collaborators from './components/Collaborators.vue';
import News from './components/News.vue';
import Footer from "@/components/Footer.vue";

export default {
  components: {
    Header, Introduction, About, Publications, Experience, Academic, Award, Collaborators: Collaborators, News, Footer
  }
}
</script>