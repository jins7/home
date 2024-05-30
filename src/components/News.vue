<template>
  <section id="news">
    <div class="pt-1"></div>
    <div class="container my-5">
      <div class="row my-5">

        <div class="d-flex align-items-center">
          <img src="../assets/icon/news.png" width="36" height="36" alt="">
          <div class="h2 m-4">News (Since June 2023)</div>
        </div>

        <ul class="list-group list-group-flush">
          <li class="list-group-item" v-for="item in news">
            <h5>{{ item.time }} : {{ item.event }}</h5>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      news: [
        { time: '2024.05', event: '2 paper were accepted to KDD (First Author).' },
        { time: '2024.04', event: '2 paper were accepted to ICML (Corresponding Author).' },
        { time: '2024.01', event: '3 paper were accepted to ICLR (1 First Author + 1 Equally Contribution).' },
        { time: '2024.01', event: '1 paper was accepted to KBS (Corresponding author).' },
        { time: '2024.01', event: '1 paper was accepted to WWW (Corresponding author).' },
        { time: '2023.12', event: '1 paper was accepted to AAAI2024 (Corresponding author).' },
        { time: '2023.11', event: '1 paper was accepted to TPAMI.' },
        { time: '2023.10', event: '1 paper was accepted to TKDE.' },
      ]
    }
  }
}
</script>