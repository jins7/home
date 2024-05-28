<template>
  <section id="academic">
    <div class="container my-5">
      <div class="row my-5">

        <div class="d-flex align-items-center">
          <img src="../assets/icon/academic.png" width="36" height="36" alt="">
          <div class="h2 m-4">Academic service</div>
        </div>

        <div class="h5 pb-2">
          PC Member/Conference Reviewer:
        </div>
        <div class="px-1">
          <ul>
            <li v-for="item in academic">
              <h5>{{ item.event }}</h5>
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
      academic: [
        { event: 'NeurIPS2023 Conference Reviewer' },
        { event: 'NeurIPS2024 Conference Reviewer' },
        { event: 'NeurIPS 2024 Datasets and Benchmarks Track Reviewer' },
        { event: 'ICLR 2022 Conference Reviewer' },
        { event: 'ICML 2024 Conference Reviewer' },
        { event: 'ACMMM 2024 Conference Reviewer' },
        { event: 'KDD 2024 Conference Reviewer' },
      ]
    }
  }
}
</script>