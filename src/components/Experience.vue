<template>
  <section id="experience">
    <div class="pt-1"></div>
    <div class="container my-5">
      <div class="row">

        <div class="d-flex align-items-center">
          <img src="../assets/icon/experience.png" width="36" height="36" alt="">
          <div class="h2 m-4">Research Experience</div>
        </div>

        <!-- <div v-for="item in news" class="col-12 col-lg-4 pb-4">
          <div class="card">
            <div class="row">
              <div class="col-6 col-lg-8 p-4 pb-2 ">
                <img :src="item.img" class="img-fluid" alt="...">
              </div>
            </div>
            <div class="card-body">
              <h5 class="pb-2">{{ item.time }} {{ item.role }}</h5>
              <h5 class="pb-2">{{ item.name }}</h5>
              <a :href="item.link">
                <h5>{{ item.leader }}</h5>
              </a>
            </div>
          </div>
        </div> -->

        <div class="col-12 col-lg-4 pb-4">
          <div class="card">
            <div class="row">
              <div class="col-6 col-lg-8 p-4 pb-2 ">
                <img src="../assets/image/ResearchExperience1.png" class="img-fluid" alt="...">
              </div>
            </div>
            <div class="card-body">
              <!--              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>-->
              <h5 class="pb-2">2023.07 - 2024.10 Research intern</h5>
              <h5 class="pb-2">CityMind Lab, Hong Kong University of Science and Technology (Guangzhou)</h5>
              <a href="https://yuxuanliang.com/">
                <h5>Advisor: Yuxuan Liang</h5>
              </a>
            </div>
          </div>
        </div>

        <div class="col-12 col-lg-4 pb-4">
          <div class="card">
            <div class="row">
              <div class="col-6 col-lg-8 p-4 pb-2 ">
                <img src="../assets/image/ResearchExperience2.png" class="img-fluid" alt="...">
              </div>
            </div>
            <div class="card-body">
              <!--              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>-->
              <h5 class="pb-2">2023.10 - 2024.06 Research intern</h5>
              <h5 class="pb-2">National University of Singapore</h5>
              <a href="https://scholar.google.com/citations?user=IDREwXEAAAAJ&hl=en&oi=ao">
                <h5>Advisor: Roger Zimmermann</h5>
              </a>
            </div>
          </div>
        </div>

        <div class="col-12 col-lg-4 pb-4">
          <div class="card">
            <div class="row">
              <div class="col-6 col-lg-8 p-4 pb-2 ">
                <img src="../assets/image/ResearchExperience3.png" class="img-fluid" alt="...">
              </div>
            </div>
            <div class="card-body">
              <!--              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>-->
              <h5 class="pb-2">2019.09-present Full PhD student</h5>
              <h5 class="pb-2">USTC</h5>
              <a href="https://faculty.ustc.edu.cn/wangyang/zh_CN/index/196617/list/">
                <h5>Advisor: Yang Wang</h5>
              </a>
            </div>
          </div>
        </div>

        <div class="col-12 col-lg-4 pb-4">
          <div class="card">
            <div class="row">
              <div class="col-6 col-lg-8 p-4 pb-2 ">
                <img src="../assets/image/img.png" class="img-fluid" alt="...">
              </div>
            </div>
            <div class="card-body">
              <!--              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>-->
              <h5 class="pb-2">2023.07-present 算法实习生</h5>
              <h5 class="pb-2">松鼠AI</h5>
              <a href="https://sites.google.com/site/qingsongwen8/">
                <h5>Advisor: 文青松</h5>
              </a>
            </div>
          </div>
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
        { time: '2023.07 - 2024.10', img: 'src/assets/image/ResearchExperience1.png', role: 'Research intern', name: 'CityMind Lab, Hong Kong University of Science and Technology (Guangzhou)', leader: 'Advisor: Yuxuan Liang', link: "https://yuxuanliang.com/" },
        { time: '2023.10 - 2024.06', img: 'src/assets/image/ResearchExperience2.png', role: 'Research intern', name: 'National University of Singapore', leader: 'Advisor: Roger Zimmermann', link: "https://scholar.google.com/citations?user=IDREwXEAAAAJ&hl=en&oi=ao" },
        { time: '2019.09-present', img: 'src/assets/image/ResearchExperience3.png', role: 'Full PhD student', name: 'USTC', leader: 'Advisor: Yang Wang', link: "https://faculty.ustc.edu.cn/wangyang/zh_CN/index/196617/list/" },
        { time: '2023.07-present', img: 'src/assets/image/ResearchExperience3.png', role: '算法实习生', name: '松鼠AI', leader: 'Advisor: 文青松', link: "https://sites.google.com/site/qingsongwen8/" },
      ]
    }
  }
}
</script>