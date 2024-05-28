<template>
  <section id="award">
    <div class="container my-5">
      <div class="row mt-5">
        <div class="d-flex align-items-center">
          <img src="../assets/icon/honor.png" width="36" height="36" alt="">
          <div class="h2 m-4">Honors and Awards</div>
        </div>

        <div class="px-1">
          <ul>
            <li v-for="item in news">
              <h5>{{ item.time }} : {{ item.event }}</h5>
            </li>
          </ul>
        </div>

      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      news: [
        { time: '2023.10', event: 'First-class Academic Scholarship of the University of Science and Technology of China.' },
        { time: '2023.04', event: 'Suzhou Industrial Park Scholarship' },
        { time: '2023.02', event: 'Global Digital Technology Scholarship' },
      ]
    }
  }
}
</script>





