<template>
  <section id="publications">
    <div class="pt-5"></div>
    <div class="container">

      <div class="d-flex align-items-center">
        <img src="../assets/icon/publications.png" width="36" height="36" alt="">
        <div class="h2 m-3">Selected Publications</div>
      </div>

      <!-- <div v-for="item in publications" class="card mb-3">
        <div class="row">
          <div class="col-md-5">
            <img class="img-fluid" :src="item.img" alt="...">
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h5 class="card-title">{{ item.name }}</h5>
              <div class="card-text h6 py-2">
                {{ item.writers }}
              </div>
              <div class="card-text h6">{{ item.type }}</div>

              <div class="row pt-4">
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" :href="item.paperUrl">Paper</a>
                </div>
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" :href="item.codeUrl">Code</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div> -->

      <div class="card mb-3">
        <div class="row">
          <div class="col-md-5">
            <img class="img-fluid" src="/src/assets/image/publications/publication1.png" alt="...">
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h5 class="card-title">The Snowflake Hypothesis Training and Powering GNN with One Node One Receptive
                field</h5>
              <div class="card-text h6 py-2">
                Kun Wang, Guohao Li, shilong wang, Guibin Zhang, Kai Wang, Yang You, Junfeng Fang, Xiaojiang Peng,
                Yuxuan Liang, Yang Wang
              </div>
              <div class="card-text h6">KDD 2024</div>

              <div class="row pt-4">
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://arxiv.org/abs/2308.10051">Paper</a>
                </div>
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://github.com/CunWang520/Snowhypothe">Code</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="card mb-3">
        <div class="row">
          <div class="col-md-5">
            <img class="img-fluid" src="/src/assets/image/publications/publication2.png" alt="...">
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h5 class="card-title">The Heterophilic Snowflake Hypothesis: <br>
                Training and Empowering GNNs for Heterophilic Graphs</h5>
              <div class="card-text h6 py-2">
                Kun Wang, Guibin Zhang, Xinnan Zhang, Junfeng Fang, Xun Wu, Guohao Li, Shirui Pan, Wei Huang, Yuxuan
                Liang
              </div>
              <div class="card-text h6">KDD 2024</div>

              <div class="row pt-4">
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="/">Paper</a>
                </div>
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="/">Code</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="card mb-3">
        <div class="row">
          <div class="col-md-5">
            <img class="img-fluid" src="/src/assets/image/publications/publication3.png" alt="...">
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h5 class="card-title">All Nodes are created Not Equal: Node-Specific Layer Aggregation and Filtration for
                GNN</h5>
              <div class="card-text h6 py-2">
                Shilong Wang, Hao Wu, Yifan Duan, Guibin Zhang, Guohao Li, Yuxuan Liang, Shirui Pan, Kun Wang, Yang Wang
              </div>
              <div class="card-text h6">Submitted</div>

              <div class="row pt-4">
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://arxiv.org/pdf/2405.07892">Paper</a>
                </div>
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://github.com/wslong20/NoSAF-NoSAF-D">Code</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="card mb-3">
        <div class="row">
          <div class="col-md-5">
            <img class="img-fluid" src="/src/assets/image/publications/publication4.png" alt="...">
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h5 class="card-title">MolTC: Towards Molecular Relational Modeling In Language Models</h5>
              <div class="card-text h6 py-2">
                Junfeng Fang and Shuai Zhang and Chang Wu Zhengyi Yang and Zhiyuan Liu and Sihang Li KunWang and
                WenjieDu and XiangWang
              </div>
              <div class="card-text h6">ACL 2024</div>

              <div class="row pt-4">
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://arxiv.org/html/2402.03781v3">Paper</a>
                </div>
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://github.com/MangoKiller/MolTC">Code</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="card mb-3">
        <div class="row">
          <div class="col-md-5">
            <img class="img-fluid" src="/src/assets/image/publications/publication5.png" alt="...">
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h5 class="card-title">Brave the Wind and the Waves: Discovering Robust and Generalizable Graph Lottery
                Tickets</h5>
              <div class="card-text h6 py-2">
                Kun Wang , Yuxuan Liang Roger Zimmermann, Xinglin Li, Guohao Li, Bernard Ghanem, Roger Zimmermann,
                Zhengyang Zhou, Huahui yi, Yudong Zhang, Yang Wang
              </div>
              <div class="card-text h6">TPAMI 2023</div>

              <div class="row pt-4">
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10356750">Paper</a>
                </div>
                <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                  <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                  <a class="px-2" href="https://github.com/CunWang520/RGLT">Code</a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="card mb-3">
        <div class="row">
          <div class="col-md-5">
            <img class="img-fluid" src="/src/assets/image/publications/publication6.png" alt="...">
          </div>
          <div class="col-md-7">
            <div class="card-body">
              <h5 class="card-title">NuwaDynamics: Discovering and Updating in Causal Spatio-Temporal Modeling</h5>
              <div class="card-text h6 py-2">
                Kun Wang, Hao Wu, Yifan Duan, Guibin Zhang, Kai Wang, Xiaojiang Peng, Yu Zheng, Yuxuan Liang, Yang Wang
              </div>
              <div class="card-text h6">ICLR 2024 (Spotlight < 5%)</div>

                  <div class="row pt-4">
                    <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                      <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                      <a class="px-2" href="/">Paper</a>
                    </div>
                    <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                      <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                      <a class="px-2" href="https://github.com/easylearningscores/NuwaDynamics">Code</a>
                    </div>
                  </div>
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-3">
          <div class="row">
            <div class="col-md-5">
              <img class="img-fluid" src="/src/assets/image/publications/publication7.png" alt="...">
            </div>
            <div class="col-md-7">
              <div class="card-body">
                <h5 class="card-title">Two heads are better than one: Boosting graph sparse training via semantic and
                  topological awareness</h5>
                <div class="card-text h6 py-2">
                  Guibin Zhang, Yanwei Yue, Kun Wang, Junfeng Fang, Yongduo Sui, Kai Wang, Yuxuan Liang, Dawei Cheng,
                  Shirui Pan, Tianlong Chen
                </div>
                <div class="card-text h6">ICML 2024</div>

                <div class="row pt-4">
                  <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                    <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                    <a class="px-2" href="https://arxiv.org/html/2402.01242v1">Paper</a>
                  </div>
                  <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                    <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                    <a class="px-2" href="https://github.com/yanweiyue/GST">Code</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <div class="card mb-3">
          <div class="row">
            <div class="col-md-5">
              <img class="img-fluid" src="/src/assets/image/publications/publication8.png" alt="...">
            </div>
            <div class="col-md-7">
              <div class="card-body">
                <h5 class="card-title">Earthfarseer: Versatile Spatio-Temporal Dynamical Systems Modeling in One Model
                </h5>
                <div class="card-text h6 py-2">
                  Hao Wu, Shilong Wang, Yuxuan Liang, Zhengyang Zhou, Wei Huang, Wei Xiong, Kun Wang
                </div>
                <div class="card-text h6">AAAI 2024</div>

                <div class="row pt-4">
                  <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                    <img src="../assets/icon/paper.png" alt="" style="height: 23px; width: 23px;">
                    <a class="px-2" href="https://ojs.aaai.org/index.php/AAAI/article/view/29521">Paper</a>
                  </div>
                  <div class="col-5 col-md-4 col-lg-3 col-xl-2">
                    <img src="../assets/icon/github.png" alt="" style="height: 23px; width: 23px;">
                    <a class="px-2" href="https://github.com/easylearningscores/EarthFarseer">Code</a>
                  </div>
                </div>
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
      publications: [
        {
          name: 'The Snowflake Hypothesis Training and Powering GNN with One Node One Receptive field',
          writers: 'Kun Wang, Guohao Li, shilong wang, Guibin Zhang, Kai Wang, Yang You, Junfeng Fang, Xiaojiang Peng, Yuxuan Liang, Yang Wang',
          type: 'KDD 2024',
          paperUrl: 'https://arxiv.org/abs/2308.10051',
          codeUrl: 'https://github.com/CunWang520/Snowhypothe',
          // OpenReviewUrl: 'https://github.com/',
          img: 'src/assets/image/publications/publication1.png'
        },
        {
          name: 'The Heterophilic Snowflake Hypothesis:\n' +
            'Training and Empowering GNNs for Heterophilic Graphs',
          writers: 'Kun Wang, Guibin Zhang, Xinnan Zhang, Junfeng Fang, Xun Wu, Guohao Li, Shirui Pan, Wei Huang, Yuxuan Liang',
          type: 'KDD 2024',
          paperUrl: '/',
          codeUrl: '/',
          // OpenReviewUrl: 'https://github.com/',
          img: 'src/assets/image/publications/publication2.png'
        },
        {
          name: 'All Nodes are created Not Equal: Node-Specific Layer Aggregation and Filtration for GNN',
          writers: 'Shilong Wang, Hao Wu, Yifan Duan, Guibin Zhang, Guohao Li, Yuxuan Liang, Shirui Pan, Kun Wang, Yang Wang',
          type: 'Submitted',
          paperUrl: 'https://arxiv.org/pdf/2405.07892',
          codeUrl: 'https://github.com/wslong20/NoSAF-NoSAF-D',
          // OpenReviewUrl: 'https://github.com/',
          img: 'src/assets/image/publications/publication3.png'
        },
        {
          name: 'MolTC: Towards Molecular Relational Modeling In Language Models',
          writers: 'Junfeng Fang and Shuai Zhang and Chang Wu Zhengyi Yang and Zhiyuan Liu and Sihang Li KunWang and WenjieDu and XiangWang',
          type: 'ACL 2024',
          paperUrl: 'https://arxiv.org/html/2402.03781v3',
          codeUrl: 'https://github.com/MangoKiller/MolTC',
          // OpenReviewUrl: 'https://github.com/',
          img: 'src/assets/image/publications/publication4.png'
        },
        {
          name: 'Brave the Wind and the Waves: Discovering Robust and Generalizable Graph Lottery Tickets',
          writers: 'Kun Wang , Yuxuan Liang Roger Zimmermann, Xinglin Li, Guohao Li, Bernard Ghanem, Roger Zimmermann, Zhengyang Zhou, Huahui yi, Yudong Zhang, Yang Wang',
          type: 'TPAMI 2023',
          paperUrl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10356750',
          codeUrl: 'https://github.com/CunWang520/RGLT',
          // OpenReviewUrl: 'https://github.com/',
          img: 'src/assets/image/publications/publication5.png'
        },
        {
          name: 'NuwaDynamics: Discovering and Updating in Causal Spatio-Temporal Modeling',
          writers: 'Kun Wang, Hao Wu, Yifan Duan, Guibin Zhang, Kai Wang, Xiaojiang Peng, Yu Zheng, Yuxuan Liang, Yang Wang',
          type: 'ICLR 2024 (Spotlight < 5%)',
          // paperUrl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10356750',
          codeUrl: 'https://github.com/easylearningscores/NuwaDynamics',
          OpenReviewUrl: 'https://openreview.net/pdf?id=sLdVl0q68X',
          img: 'src/assets/image/publications/publication6.png'
        },
        {
          name: 'Two heads are better than one: Boosting graph sparse training via semantic and topological awareness',
          writers: 'Guibin Zhang, Yanwei Yue, Kun Wang, Junfeng Fang, Yongduo Sui, Kai Wang, Yuxuan Liang, Dawei Cheng, Shirui Pan, Tianlong Chen',
          type: 'ICML 2024',
          paperUrl: 'https://arxiv.org/html/2402.01242v1',
          codeUrl: 'https://github.com/yanweiyue/GST',
          // OpenReviewUrl: 'https://openreview.net/pdf?id=sLdVl0q68X',
          img: 'src/assets/image/publications/publication7.png'
        },
        {
          name: 'Earthfarseer: Versatile Spatio-Temporal Dynamical Systems Modeling in One Model',
          writers: 'Hao Wu, Shilong Wang, Yuxuan Liang, Zhengyang Zhou, Wei Huang, Wei Xiong, Kun Wang',
          type: 'AAAI 2024',
          paperUrl: 'https://ojs.aaai.org/index.php/AAAI/article/view/29521',
          codeUrl: 'https://github.com/easylearningscores/EarthFarseer',
          // OpenReviewUrl: 'https://openreview.net/pdf?id=sLdVl0q68X',
          img: 'src/assets/image/publications/publication8.png'
        },
      ]
    }
  },
}
</script>
