<template>
  <section id="collaborators">
    <div class="container my-5">
      <div class="row">
        <div class="d-flex align-items-center">
          <img src="../assets/icon/collaborators.png" width="36" height="36" alt="">
          <div class="h2 m-4">Collaborators</div>
        </div>

        <div class="col-12 col-lg-10 pb-4">
          <div class="card">
            <div class="row align-items-center justify-content-center">
              <div class="col-3 col-md-2 p-3">
                <img src="/src/assets/image/Oxford.png" class="img-fluid" alt="...">
              </div>
              <div class="col-3 col-md-2 p-3">
                <img src="/src/assets/image/MIT.png"  class="img-fluid" alt="...">
              </div>
              <div class="col-5 col-md-4 p-3">
                <img src="/src/assets/image/ResearchExperience2.png"  class="img-fluid" alt="...">
              </div>
              <div class="col-3 col-md-2 p-3">
                <img src="/src/assets/image/Griffith.png"  class="img-fluid" alt="...">
              </div>
              <div class="col-5 p-3">
                <img src="/src/assets/image/ResearchExperience1.png"  class="img-fluid" alt="...">
              </div>
              <div class="col-6 p-3">
                <img src="/src/assets/image/ResearchExperience3.png"  class="img-fluid" alt="...">
              </div>
            </div>
            <div class="card-body">
              <ul>
                <li v-for="item in collaborators2">
                  <h5><a :href="item.link" >{{ item.name }}</a>, {{ item.role }}, {{ item.workplace }}</h5>
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="col-12 col-lg-6">
          <div class="card">
            <div class="row px-4 align-items-center justify-content-center">
              <div class="col-4 col-md-3 p-3">
                <img src="/src/assets/image/TongJi.png"  class="img-fluid" alt="...">
              </div>
              <div class="col-4 col-md-3 p-3">
                <img src="/src/assets/image/Tianjin.png"  class="img-fluid" alt="...">
              </div>
              <div class="col-6 p-3">
                <img src="/src/assets/image/ResearchExperience2.png"  class="img-fluid" alt="...">
              </div>
              <div class="col-6 p-3">
                <img src="/src/assets/image/ResearchExperience3.png"  class="img-fluid" alt="...">
              </div>
            </div>

            <div class="card-body">
              <div class="col-12 h4 pb-2">Mentoring</div>
              <div class="h5">Direction:  Spatio-temporal Data Ming</div>
              <ul>
                <li v-for="item in collaborators3">
                  <h5><a :href="item.link" >{{ item.name }}</a>, {{ item.role }}, {{ item.workplace }}</h5>
                </li>
              </ul>
              <div class="h5">Direction:  Efficient AI</div>
              <ul>
                <li v-for="item in collaborators4">
                  <h5><a :href="item.link" >{{ item.name }}</a>, {{ item.role }}, {{ item.workplace }}</h5>
                </li>
              </ul>

              <div class="h5">Direction: LLM saftey & Agent</div>
              <ul>
                <li v-for="item in collaborators5">
                  <h5><a :href="item.link" >{{ item.name }}</a>, {{ item.role }}, {{ item.workplace }}</h5>
                </li>
              </ul>
            </div>
          </div>
        </div>

        <div class="col-12 col-lg-6">
          <div class="card">
            <img src="/src/assets/image/collaborators/collaborators1.png" class="col-8 p-4" alt="...">
            <div class="card-body">
              <ul>
                <li v-for="item in collaborators1">
                  <h5><a :href="item.link" >{{ item.name }}</a>, {{ item.role }}</h5>
                </li>
              </ul>
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
      collaborators1: [
        { name: 'Zhengyang Zhou', role:'Associate Researcher', link:"http://home.ustc.edu.cn/~zzy0929/Home/" },
        { name: 'Pengkun Wang', role:'Associate Researcher', link:"http://home.ustc.edu.cn/~pengkun/index.html" },
        { name: 'Wenjie Du', role:'Associate Researcher', link:"/" },
        { name: 'Xu Wang', role:'Associate Researcher', link:"http://home.ustc.edu.cn/~wx309/index.html" },
        { name: 'Yudong Zhang', role:'Associate Researcher', link:"http://home.ustc.edu.cn/~zyd2020/" },
        { name: 'Binwu Wang', role:'Associate Researcher', link:"/" },
        { name: 'Chen Zhang, Kuo Yang, Zhe Zhao', role:'PhD Candidates', link:"/" },
      ],
      collaborators2: [
        { name: 'Yuxuan Liang', role:'Assistant Professor', workplace:'INTR & DSA Thrust, HKUST(GZ)', link:"https://yuxuanliang.com/" },
        { name: 'Tianlong chen', role:'Assistant Professor', workplace:'MIT', link:"https://scholar.google.com/citations?user=LE3ctn0AAAAJ&hl=en" },
        { name: 'Guohao Li', role:'Postdoc', workplace:'University of Oxford', link:"https://scholar.google.com/citations?user=J9K-D0sAAAAJ&hl=en" },
        { name: 'Kai Wang', role:'Postdoc', workplace:'NUS', link:"https://scholar.google.com/citations?user=i2II0XIAAAAJ&hl=en" },
        { name: 'Shirui Pan', role:'Full Professor, ARC Future Fellow', workplace:'Griffith University', link:"https://scholar.google.com/citations?user=frWRJN4AAAAJ&hl=en" },
        { name: 'Roger Zimmermann', role:'Full Professor', workplace:'NUS', link:"https://scholar.google.com/citations?user=IDREwXEAAAAJ&hl=en" },
        { name: 'Qingsong Wen', role:'Head of AI Research & Chief Scientist', workplace:'Squirrel AI', link:"https://scholar.google.com/citations?user=vjPJvwYAAAAJ&hl=en" },
        { name: 'JunFeng Fang', role:'PhD', workplace:'USTC', link:"https://scholar.google.com/citations?user=9jdGFpEAAAAJ&hl=en" },
      ],
      collaborators3: [
        { name: 'Hao Wu', workplace:'USTC', link:"https://easylearningscores.github.io/" },
        { name: 'Yifan Duan', workplace:'USTC', link:"/" },
        { name: 'Junyuan Mao', workplace:'USTC', link:"/" },
      ],
      collaborators4: [
        { name: 'Guibin Zhang', workplace:'Tongji University', link:"https://guibinz.top/" },
        { name: 'Shilong Wang', workplace:'USTC', link:"/" },
        { name: 'Xinglin Li', workplace:'Tianji University', link:"/" },
      ],
      collaborators5: [
        { name: 'Cifan Meng', workplace:'USTC', link:"/" },
        { name: 'Ruixiang Wang', workplace:'NUS', link:"/" },
      ],
    }
  }
}
</script>