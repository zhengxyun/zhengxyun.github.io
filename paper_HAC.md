---
layout: paper_page
permalink: /paper_hac/
---

<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="description"
        content="Fast Stitching Model Families for Efficient Model Deployment">
  <meta name="keywords" content="Vision Transformers, DeiT, Swin">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Stitchable Neural Networks</title>

  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-HCEYYEQ773"></script>
  <script>
    window.dataLayer = window.dataLayer || [];

    function gtag() {
      dataLayer.push(arguments);
    }

    gtag('js', new Date());

    gtag('config', 'G-HCEYYEQ773');
  </script>

  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro"
        rel="stylesheet">

  <link rel="stylesheet" href="./static/css/bulma.min.css">
  <link rel="stylesheet" href="./static/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="./static/css/bulma-slider.min.css">
  <link rel="stylesheet" href="./static/css/fontawesome.all.min.css">
  <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="./static/css/index.css">
  <link rel="icon" href="./static/images/favicon.svg">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script defer src="./static/js/fontawesome.all.min.js"></script>
  <script src="./static/js/bulma-carousel.min.js"></script>
  <script src="./static/js/bulma-slider.min.js"></script>
  <script src="./static/js/index.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>
  
<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>
  <div class="navbar-menu">
    <div class="navbar-start" style="flex-grow: 1; justify-content: center;">
      <a class="navbar-item" href="https://github.com/ziplab">
      <span class="icon">
          <i class="fas fa-home"></i>
      </span>
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          More Research
        </a>
        <div class="navbar-dropdown">
          <a class="navbar-item" href="https://snnet.github.io/snnetv2/">
            SN-Netv2
          </a>
          <a class="navbar-item" href="https://t-stitch.github.io/">
            T-Stitch
          </a>
          <a class="navbar-item" href="https://arxiv.org/abs/2311.17352">
            ESTA
          </a>
        </div>
      </div>
    </div>

  </div>
</nav>

<!-- <div class="containerx">
  <img src="./static/images/banner_new.png" alt="Avatar" class="imagex">
  <div class="banner-text"><center>Stitchable Neural Networks</center></div>
</div> -->

<section class="hero">
  <div class="hero-body">
    <div class="container is-max-desktop">
      <div class="columns is-centered">
        <div class="column has-text-centered">
          <h1 class="title is-1 publication-title">Stitchable Neural Networks</h1>
          <h4 class="title is-4 publication-title">CVPR 2023 Highlight</h4>
          <div class="is-size-5 publication-authors">
            <span class="author-block">
              <a href="https://zizhengpan.github.io/">Zizheng Pan</a>,</span>
            <span class="author-block">
              <a href="https://jianfei-cai.github.io/">Jianfei Cai</a>,</span>
            <span class="author-block">
              <a href="https://bohanzhuang.github.io/">Bohan Zhuang</a>
            </span>
          </div>

          <div class="is-size-5 publication-authors">
            <span class="author-block">ZIP Lab, Monash University</span>
            <!-- <span class="author-block"><sup>2</sup>Google Research</span> -->
          </div>

          <div class="column has-text-centered">
            <div class="publication-links">
              <!-- PDF Link. -->
              <span class="link-block">
                <a href="https://arxiv.org/pdf/2302.06586.pdf"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fas fa-file-pdf"></i>
                  </span>
                  <span>Paper</span>
                </a>
              </span>
              <span class="link-block">
                <a href="https://arxiv.org/abs/2302.06586"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="ai ai-arxiv"></i>
                  </span>
                  <span>arXiv</span>
                </a>
              </span>
              <!-- Video Link. -->
              <!-- <span class="link-block">
                <a href="https://www.youtube.com/watch?v=MrKrnHhk8IA"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fab fa-youtube"></i>
                  </span>
                  <span>Video</span>
                </a>
              </span> -->
              <!-- Code Link. -->
              <span class="link-block">
                <a href="https://github.com/ziplab/SN-Net"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fab fa-github"></i>
                  </span>
                  <span>Code</span>
                  </a>
              </span>
              <!-- Dataset Link. -->
              <!-- <span class="link-block">
                <a href="https://github.com/google/nerfies/releases/tag/0.1"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="far fa-images"></i>
                  </span>
                  <span>Data</span>
                  </a> -->
            </div>

          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="hero teaser">
  <div class="container is-max-desktop">
    <div class="hero-body">
      <img src="./static/images/banner.png">
      <h2 class="subtitle has-text-centered">
        <span class="dnerf">Stitchable Neural NETwork directly stitches the off-the-rack family of pretrained models and quickly obtains new networks for efficient model design and deployment in a novel many-to-many paradigm.
      </h2>
    </div>
  </div>
</section>



<section class="section">


  <div class="container is-max-desktop">


<div class="container is-max-desktop">
  <div class="columns is-centered has-text-centered">
    <h2 class="title is-3">Challenging 200 Models with a Single Network</h2>
    </div>
    <div class="column ">
      <div class="content has-text-justified">
        <p><i>One</i> Stitchable Neural Network v.s <i>200</i> models in Timm model zoo. 
          It shows an example of SN-Net by stitching ImageNet-22K pretrained Swin-Ti/S/B. 
          Compared to each individual network, SN-Net is able to <i><b>instantly switch network topology
           at runtime </b></i> and covers a wide range of computing resource budgets. 
           Larger dots indicate a larger model with more parameters and higher complexity. Click the legend label (e.g., <font style="color:#AF6FAB;">Timm Models</font> and  <font style="color:#26959D;">Stitched Nets</font>) for selective visualization.
           Hover the dots to check the detail of each model.
          </p>
      </div>
    </div>

    <center>
      <div style="position: relative;height:60vh;">
        <canvas id="myChart"></canvas>
    </div>
    </center>
</div>

<script>
  const ctx = document.getElementById('myChart');
  var my_data = [[10.46, 86.09], [15.38, 85.82], [15.47, 85.25], [14.34, 85.19], [15.46, 85.03], [15.52, 84.82], [14.14, 84.71], [8.71, 84.57], [6.43, 84.5], [8.44, 84.3], [16.48, 84.29], [16.13, 84.28], [10.46, 84.25], [6.35, 84.24], [12.82, 84.21], [6.94, 84.16], [12.5, 84.14], [13.14, 84.08], [6.19, 84.05], [7.03, 84.05], [10.43, 84.05], [9.33, 84.02], [14.92, 84.01], [13.69, 83.93], [13.22, 83.93], [8.44, 83.88], [9.1, 83.87], [11.58, 83.85], [15.38, 83.84], [10.46, 83.81], [8.72, 83.81], [15.52, 83.8], [9.43, 83.77], [10.56, 83.72], [10.55, 83.71], [15.15, 83.68], [9.08, 83.49], [9.35, 83.46], [15.52, 83.43], [9.74, 83.41], [16.24, 83.4], [12.62, 83.38], [13.06, 83.35], [8.01, 83.24], [8.77, 83.22], [6.6, 83.2], [13.96, 83.17], [8.71, 83.15], [8.59, 83.14], [9.07, 83.14], [9.84, 83.14], [13.91, 83.13], [10.35, 83.12], [6.61, 83.04], [16.48, 83.02], [12.47, 82.93], [13.38, 82.89], [11.56, 82.82], [6.68, 82.81], [6.55, 82.81], [7.13, 82.75], [14.59, 82.72], [6.68, 82.71], [16.48, 82.7], [10.6, 82.65], [16.13, 82.64], [9.2, 82.59], [9.1, 82.58], [7.12, 82.58], [6.87, 82.57], [8.03, 82.56], [9.21, 82.56], [9.5, 82.52], [9.87, 82.52], [7.97, 82.46], [11.59, 82.46], [12.42, 82.44], [9.05, 82.4], [14.13, 82.39], [8.07, 82.36], [8.82, 82.35], [7.22, 82.33], [6.13, 82.33], [12.62, 82.3], [7.97, 82.29], [13.56, 82.28], [7.96, 82.24], [10.6, 82.22], [14.35, 82.19], [8.08, 82.17], [8.8, 82.11], [15.17, 82.06], [7.83, 82.05], [7.15, 81.98], [9.25, 81.97], [7.83, 81.93], [9.21, 81.9], [7.24, 81.82], [6.16, 81.78], [8.52, 81.62], [16.48, 81.61], [10.88, 81.49], [11.43, 81.46], [8.0, 81.31], [6.82, 81.27], [8.91, 81.16], [7.22, 81.14], [12.92, 81.01], [5.4, 80.97], [9.63, 80.96], [5.42, 80.93], [8.01, 80.92], [8.02, 80.91], [6.16, 80.89], [15.53, 80.88], [5.9, 80.87], [5.54, 80.86], [5.96, 80.76], [6.88, 80.65], [15.52, 80.6], [11.78, 80.54], [10.08, 80.52], [11.8, 80.48], [13.18, 80.46], [8.08, 80.42], [12.14, 80.38], [16.62, 80.34], [8.01, 80.34], [8.0, 80.3], [9.19, 80.3], [8.0, 80.25], [8.02, 80.22], [12.28, 80.17], [6.57, 80.06], [6.54, 80.02], [13.18, 79.97], [11.8, 79.91], [15.99, 79.85], [5.24, 79.85], [16.09, 79.83], [8.91, 79.77], [13.96, 79.72], [11.56, 79.68], [11.73, 79.64], [12.13, 79.59], [8.08, 79.54], [7.68, 79.49], [9.34, 79.44], [5.96, 79.38], [12.63, 79.37], [16.48, 79.32], [7.09, 79.31], [7.83, 79.3], [5.16, 79.29], [8.02, 79.2], [8.1, 79.2], [6.49, 79.07], [8.4, 79.04], [8.37, 78.95], [12.75, 78.92], [14.94, 78.9], [5.73, 78.81], [5.47, 78.71], [11.6, 78.68], [11.33, 78.65], [6.33, 78.57], [9.28, 78.52], [5.89, 78.51], [8.97, 78.45], [7.61, 78.38], [13.16, 78.37], [11.56, 78.32], [8.15, 78.2], [5.28, 78.04], [7.19, 78.03], [4.28, 77.96], [5.73, 77.85], [6.34, 77.82], [4.26, 77.62], [8.15, 77.59], [4.11, 77.58], [5.73, 77.58], [4.18, 77.52], [5.73, 77.44], [7.83, 77.38], [7.79, 77.35], [4.34, 77.29], [4.26, 77.02], [5.55, 76.94], [4.32, 76.76], [12.62, 76.61], [5.7, 76.46], [4.11, 76.13], [4.41, 73.69], [15.5, 73.35], [11.33, 71.6], [15.47, 71.59], [7.62, 70.36], [11.31, 69.93], [7.61, 69.03]]
  var timm_params = [30.39, 88.59, 87.77, 58.68, 57.7, 22.21, 26.25, 50.22, 28.94, 21.46, 88.79, 84.4, 30.39, 27.12, 49.73, 26.63, 74.79, 28.59, 23.37, 23.46, 36.47, 27.58, 41.41, 71.13, 39.18, 21.46, 47.67, 49.73, 88.59, 30.39, 23.94, 22.2, 49.74, 30.58, 30.58, 99.27, 49.7, 46.92, 22.21, 54.3, 18.45, 71.49, 88.3, 44.18, 49.61, 20.64, 39.92, 50.22, 56.07, 49.7, 60.99, 39.82, 38.35, 20.65, 44.57, 14.25, 48.28, 60.19, 28.35, 38.31, 35.07, 47.82, 43.83, 88.79, 35.4, 84.4, 10.59, 47.67, 24.14, 12.12, 38.76, 12.11, 44.27, 36.85, 38.75, 73.47, 73.76, 43.27, 6.71, 35.7, 25.57, 18.45, 28.21, 59.88, 38.73, 63.62, 38.74, 35.05, 17.37, 44.57, 56.17, 78.44, 44.54, 25.59, 26.91, 44.55, 12.11, 25.57, 21.91, 25.56, 88.79, 55.99, 68.88, 10.59, 10.34, 44.69, 18.45, 60.32, 27.48, 12.03, 25.9, 44.18, 48.96, 21.16, 88.23, 21.15, 14.25, 30.02, 25.56, 83.46, 41.61, 36.02, 60.21, 55.84, 44.57, 51.82, 25.55, 44.18, 10.59, 44.67, 10.59, 48.96, 42.68, 27.64, 37.67, 55.84, 60.21, 54.28, 16.01, 79.25, 44.69, 39.92, 60.19, 61.57, 46.11, 44.57, 119.42, 41.28, 30.02, 61.76, 88.79, 24.57, 44.55, 25.56, 39.57, 45.21, 26.21, 22.86, 48.4, 57.56, 67.06, 23.83, 25.68, 53.39, 66.82, 37.05, 26.97, 26.31, 41.23, 49.33, 57.42, 60.19, 37.71, 24.72, 33.27, 25.7, 23.83, 3.05, 25.03, 39.97, 25.56, 23.83, 25.29, 23.83, 44.55, 28.68, 20.01, 22.04, 24.38, 21.3, 59.88, 28.21, 25.56, 88.22, 138.37, 133.05, 138.36, 132.87, 133.05, 132.86]
  for (let i = 0; i < timm_params.length; i++) {
    timm_params[i] = timm_params[i] / 6
  }
  timm_names = ["tf_efficientnet_b5_ns", "convnext_base_in22ft1k", "swin_base_patch4_window7_224", "volo_d2_224", "regnetz_e8", "deit3_small_patch16_384_in21ft1k", "xcit_small_12_p16_384_dist", "convnext_small_in22ft1k", "regnetz_040h", "tf_efficientnetv2_s_in21ft1k", "swsl_resnext101_32x8d", "xcit_medium_24_p16_224_dist", "tf_efficientnet_b5_ap", "regnetz_040", "swinv2_small_window16_256", "volo_d1_224", "pit_b_distilled_224", "convnext_tiny_384_in22ft1k", "regnetz_d8", "regnetz_d8_evos", "vit_small_r26_s32_384", "regnetz_d32", "eca_nfnet_l1", "swin_s3_base_224", "regnety_080", "tf_efficientnetv2_s", "xcit_small_24_p16_224_dist", "swinv2_small_window8_256", "convnext_base", "tf_efficientnet_b5", "efficientnetv2_rw_s", "vit_small_patch16_384", "swin_s3_small_224", "regnety_064", "regnetv_064", "twins_svt_large", "swinv2_cr_small_ns_224", "cait_s24_224", "deit3_small_patch16_384", "sequencer2d_l", "mobilevitv2_200_384_in22ft1k", "dm_nfnet_f0", "vit_base_patch32_384", "swsl_resnext101_32x4d", "swin_small_patch4_window7_224", "regnetv_040", "xception65", "convnext_small", "twins_svt_base", "swinv2_cr_small_224", "twins_pcpvt_large", "xception65p", "jx_nest_small", "regnety_040", "resnet101d", "mobilevitv2_175_384_in22ft1k", "resnest101e", "resnet152", "swinv2_tiny_window16_256", "sequencer2d_m", "nfnet_l0", "cs3edgenet_x", "twins_pcpvt_base", "ig_resnext101_32x8d", "cs3sedarknet_x", "xcit_medium_24_p16_224", "mobilevitv2_150_384_in22ft1k", "xcit_small_24_p16_224", "eca_nfnet_l0", "xcit_tiny_24_p16_384_dist", "vit_relpos_medium_patch16_cls_224", "xcit_tiny_24_p8_224_dist", "crossvit_18_dagger_240", "resnet61q", "vit_relpos_medium_patch16_224", "poolformer_m48", "pit_b_224", "crossvit_18_240", "xcit_tiny_12_p8_384_dist", "resnet51q", "ecaresnet50t", "mobilevitv2_200_in22ft1k", "crossvit_15_dagger_240", "mixer_b16_224_miil", "vit_relpos_medium_patch16_rpn_224", "resnetrs101", "vit_srelpos_medium_patch16_224", "cs3darknet_x", "cait_xxs36_384", "ecaresnet101d", "poolformer_m36", "tresnet_xl", "resnetv2_101", "resnetv2_50d_evos", "xception41p", "resnet101", "xcit_tiny_24_p8_224", "resnetv2_50d_gn", "cs3sedarknet_l", "resnetaa50", "ssl_resnext101_32x8d", "tresnet_l", "wide_resnet50_2", "efficientnet_el", "coat_mini", "resmlp_36_distilled_224", "mobilevitv2_200", "gluon_resnet152_v1s", "resnest50d", "cait_xxs24_384", "gcresnet50t", "ssl_resnext101_32x4d", "gluon_seresnext101_32x4d", "cs3darknet_l", "gluon_seresnext101_64x4d", "cs3darknet_focus_l", "mobilevitv2_175", "resmlp_24_distilled_224", "nf_resnet50", "gluon_resnext101_64x4d", "darknet53", "darknetaa53", "gluon_resnet152_v1d", "inception_resnet_v2", "gluon_resnet101_v1d", "regnety_120", "resnetv2_50x1_bitm", "gluon_resnext101_32x4d", "efficientnet_el_pruned", "gluon_resnet101_v1s", "tf_efficientnet_el", "legacy_seresnext101_32x4d", "inception_v4", "cspdarknet53", "dpn92", "ens_adv_inception_resnet_v2", "gluon_resnet152_v1c", "regnetx_160", "ecaresnet26t", "dpn131", "resmlp_36_224", "gluon_xception65", "gluon_resnet152_v1b", "dpn98", "regnetx_120", "gluon_resnet101_v1c", "vit_relpos_base_patch32_plus_rpn_256", "dla102x2", "resmlp_24_224", "repvgg_b2g4", "resnext101_32x8d", "ese_vovnet39b", "gluon_resnet101_v1b", "resnetblur50", "regnetx_080", "res2net101_26w_4s", "regnetx_064", "xception", "res2net50_26w_8s", "hrnet_w40", "hrnet_w44", "gluon_inception_v3", "gluon_resnet50_v1s", "dla169", "legacy_seresnet152", "res2net50_26w_6s", "xception41", "dla102x", "hrnet_w32", "legacy_seresnet101", "repvgg_b1", "tv_resnet152", "hrnet_w30", "gmixer_24_224", "dla102", "res2net50_26w_4s", "tf_inception_v3", "xcit_nano_12_p8_384_dist", "tv_resnext50_32x4d", "repvgg_b1g4", "gluon_resnet50_v1b", "adv_inception_v3", "res2net50_48w_2s", "inception_v3", "tv_resnet101", "densenet161", "densenet201", "dla60", "convmixer_1024_20_ks9_p14", "hrnet_w18", "mixer_b16_224", "repvgg_a2", "tv_resnet50", "vit_base_patch32_224_sam", "vgg16_bn", "vgg13_bn", "vgg16", "vgg11_bn", "vgg13", "vgg11"]
  var swin_params = [28.29, 29.84, 31.62, 33.39, 33.39, 35.17, 36.95, 36.95, 38.72, 40.5, 40.5, 42.28, 44.05, 44.05, 45.83, 47.61, 47.61, 49.61, 49.57, 49.38, 49.62, 63.01, 64.38, 65.76, 67.14, 68.52, 69.9, 71.28, 72.66, 74.03, 75.41, 76.79, 78.17, 79.55, 80.93, 82.31, 83.68, 85.06, 87.17, 87.69, 87.77]
  var swin_data = [[4.51, 79.49], [4.89, 80.22], [5.25, 81.05], [5.6, 81.3], [5.6, 81.67], [5.96, 82.14], [6.31, 82.53], [6.31, 82.35], [6.67, 82.83], [7.02, 83.24], [7.02, 82.84], [7.38, 83.27], [7.73, 83.36], [7.73, 83.32], [8.09, 83.44], [8.44, 83.39], [8.44, 83.4], [8.77, 83.65], [8.8, 83.44], [8.8, 83.43], [8.8, 83.46], [9.67, 83.43], [9.94, 83.57], [10.21, 83.67], [10.48, 83.86], [10.76, 83.89], [11.03, 83.97], [11.3, 83.96], [11.57, 84.08], [11.85, 84.19], [12.12, 84.14], [12.39, 84.32], [12.66, 84.24], [12.94, 84.27], [13.21, 84.24], [13.48, 84.29], [13.75, 84.27], [14.03, 84.27], [14.62, 84.16], [15.22, 84.28], [15.47, 84.32]]
  for (let i = 0; i < swin_params.length; i++) {
    swin_params[i] = swin_params[i] / 6
  }

  var anchor_data = [[4.51, 79.49], [8.77, 83.65], [15.47, 84.32]]
  var anchor_names = ['Swin-Ti', 'Swin-S', 'Swin-B']
  var anchor_params = [28.29, 49.61, 87.77]
  for (let i = 0; i < anchor_params.length; i++) {
    anchor_params[i] = anchor_params[i] / 6
  }

  let width, height, gradient;
  function getGradient(ctx, chartArea) {
    const chartWidth = chartArea.right - chartArea.left;
    const chartHeight = chartArea.bottom - chartArea.top;
    if (!gradient || width !== chartWidth || height !== chartHeight) {
      width = chartWidth;
      height = chartHeight;
      gradient = ctx.createLinearGradient(0, chartHeight/2, chartWidth, chartHeight/2);
      gradient.addColorStop(0, '#ff6384');
      gradient.addColorStop(1, '#8476C1');
    }

    return gradient;
  }


new Chart(ctx, {
    data: {
      datasets: [
        {
          data: anchor_data,
          pointRadius: anchor_params,
          pointHoverRadius: 30,
          borderColor: '#D78D4A',
          backgroundColor: '#FFB92F',
          label: 'Swin Anchors',
          pointStyle: 'rectRot',
          type: 'scatter',
        },
        {
          data: swin_data,
          pointRadius: swin_params,
          pointHoverRadius: 30,
          borderColor: '#26959D',
          backgroundColor: '#B0E3E6',
          label: 'Stitched Nets',
          type: 'line',
          tension: 0.5
        },

        {
          data: my_data,
          pointRadius: timm_params,
          pointHoverRadius: 30,
          borderColor: '#FFFFFF',
          backgroundColor: function(context) {
            const chart = context.chart;
            const {ctx, chartArea} = chart;

            if (!chartArea) {
              // This case happens on initial chart load
              return;
            }
            return getGradient(ctx, chartArea);
          },
          // borderColor: '#6A98BC',
          // backgroundColor: '#9FB8D0',
          label: 'Timm Models',
          type: 'scatter',
        }
      ],
    },
    options: {
      plugins: {
        legend: {
                labels: {
                    font: {
                        size: 16
                    }
                }
            },
        customCanvasBackgroundColor: {
        color: 'lightGreen',
      },
        tooltip: {
          callbacks: {
            title: function(context) {
              // console.log(context)
              if (context[0].datasetIndex === 1) {
                return 'Stitched Net'
              }
              if (context[0].datasetIndex === 2) {
                return timm_names[context[0].dataIndex]
              }
            },
            label: function(context) {
              // console.log(context)
              if (context.datasetIndex === 2) {
                temp =  my_data[context.dataIndex]
                return temp[0] + 'G, ' + temp[1] + '%'
              }
              
              if (context.datasetIndex === 1) {
                temp =  swin_data[context.dataIndex]
                return temp[0] + 'G, ' + temp[1] + '%'
              }

            }
          }
        }
      },
      scales: {
        x: {
          ticks: {
            // color: '#000000',
                font: {
                    size: 14,
                }
            },
          title: {
            display: true,
            text: 'FLOPs (G)',
            font: {
                      size: 16
                  }
          }
        },
        y: {
        ticks: {
          // color: '#000000',
              font: {
                  size: 14,
              }
          },
        title: {
          display: true,
          text: 'ImageNet-1K Top-1 Accuracy (%)',
          font: {
                    size: 16
                }
        }
        },
      },
    }
  });

</script>


        <!-- Paper video. -->
        <!-- <div class="columns is-centered has-text-centered">
          <div class="column ">
            <h2 class="title is-3">Challenging 200 Models with a Single Network</h2>
            <div class="content has-text-justified">
              <p><i>One</i> Stitchable Neural Network v.s <i>200</i> models in Timm model zoo. 
                It shows an example of SN-Net by stitching ImageNet-22K pretrained Swin-Ti/S/B. 
                Compared to each individual network, SN-Net is able to instantly switch network topology
                 at runtime and covers a wide range of computing resource budgets. 
                 Larger and darker dots indicate a larger model with more parameters and higher complexity.
                </p>
              <img src="./static/images/compare_model_zoos.png">
            </div>
          </div>
        </div> -->
    <!-- Abstract. -->
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Abstract</h2>
        <div class="content has-text-justified">
          <p>
            The public model zoo containing enormous powerful pretrained model families (e.g., ResNet/DeiT) has reached an unprecedented 
            scope than ever, which significantly contributes to the success of deep learning. As each model family consists of pretrained 
            models with diverse scales (e.g., DeiT-Ti/S/B), it naturally arises a fundamental question of how to efficiently assemble these 
            readily available models in a family for dynamic accuracy-efficiency trade-offs at runtime. 
          </p>
          <p>
             To this end, we present <span class="dnerf"></span>Stitchable Neural Networks</span> (SN-Net), a novel scalable and efficient 
             framework for model deployment. It cheaply produces numerous networks with different complexity and performance trade-offs 
             given a family of pretrained neural networks, which we call anchors. Specifically, SN-Net splits the anchors across the 
             blocks/layers and then stitches them together with simple stitching layers to map the activations from one anchor to another.
          </p>
          <p>
            With only a few epochs of training, SN-Net effectively interpolates between the performance of anchors with varying scales. 
            At runtime, SN-Net can instantly adapt to dynamic resource constraints by switching the stitching positions. Extensive 
            experiments on ImageNet classification demonstrate that SN-Net can obtain on-par or even better performance than many 
            individually trained networks while supporting diverse deployment scenarios. For example, by stitching Swin Transformers, 
            we challenge hundreds of models in Timm model zoo with a single network. We believe this new elastic model framework can 
            serve as a strong baseline for further research in wider communities.
          </p>
        </div>
      </div>
    </div>
    <!--/ Abstract. -->


  </div>
</section>


<section class="section">
  <div class="container is-max-desktop">

    <!-- Paper video. -->
    <div class="columns is-centered has-text-centered">
      <div class="column ">
        <h2 class="title is-3">Method</h2>
        <div class="content has-text-justified">
          <p>Illustration of the proposed <i>Stitchable Neural Network</i>, where 
            three pretrained variants of DeiTs are connected with simple stitching layers 
            (1x1 convolution). We share the same stitching layer among neighboring blocks 
            (e.g., 2 in this example) between two models. Apart from the basic anchor models, 
            we obtain many sub-networks (stitches) by stitching the nearest pairs of anchors in complexity, 
            e.g., DeiT-Ti and DeiT-S <font style="color:#0066CC;">(the blue line)</font>, DeiT-S and DeiT-B <font style="color:#2A9D8F">(the green line)</font>.
            </p>
          <img src="./static/images/framework.png">
        </div>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container is-max-desktop">

    <div class="columns is-centered">

      <!-- Visual Effects. -->
      <div class="column">
        <div class="content">
          <center><h2 class="title is-3">Stitching DeiTs</h2></center>
          <center>
            <p>
              Assembling pretrained DeiT-Ti/S/B on ImageNet-1K with 50 epochs training.
            </p>
          </center>
          <img src="./static/images/main_deit_website.png">
          
          <!-- <video id="dollyzoom" autoplay controls muted loop playsinline height="100%">
            <source src="./static/videos/dollyzoom-stacked.mp4"
                    type="video/mp4">
          </video> -->
        </div>
      </div>
      <!--/ Visual Effects. -->

      <!-- Matting. -->
      <div class="column">
        <div class="content">
          <center><h2 class="title is-3">Stitching Swins</h2></center>
          <!-- <p>
            Using <i>nerfies</i> you can create fun visual effects. This Dolly zoom effect
            would be impossible without nerfies since it would require going through a wall.
          </p> -->
          <center><p>Assembling pretrained Swin-Ti/S/B on ImageNet-1K with 50 epochs training</p></center>

          <img src="./static/images/main_swin_website.png">
        </div>
      </div>
    </div>
    <!--/ Matting. -->

    <div class="columns is-centered">

      <!-- Visual Effects. -->
      <div class="column">
        <div class="content">
          <center><h2 class="title is-3">Stitching ResNets</h2></center>
          <center>
            <p>
              Assembling pretrained DeiT-Ti/S/B on ImageNet-1K with 50 epochs training.
            </p>
          </center>
          <img src="./static/images/stitch_resnet.png">
          
          <!-- <video id="dollyzoom" autoplay controls muted loop playsinline height="100%">
            <source src="./static/videos/dollyzoom-stacked.mp4"
                    type="video/mp4">
          </video> -->
        </div>
      </div>
      <!--/ Visual Effects. -->

      <!-- Matting. -->
      <div class="column">
        <div class="content">
          <center><h2 class="title is-3">Stitching ResNet and Swin</h2></center>
          <!-- <p>
            Using <i>nerfies</i> you can create fun visual effects. This Dolly zoom effect
            would be impossible without nerfies since it would require going through a wall.
          </p> -->
          <center><p>Assembling pretrained Swin-Ti/S/B on ImageNet-1K with 50 epochs training</p></center>

          <img src="./static/images/stitch_resnet_swin.png">
        </div>
      </div>
    </div>




    <!-- Concurrent Work. -->
    <!-- <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Related Links</h2>
        <div class="content has-text-justified">
          <p>
            There's a lot of excellent work that was introduced around the same time as ours.
          </p>
          <p>
            <a href="https://arxiv.org/abs/2104.09125">Progressive Encoding for Neural Optimization</a> introduces an idea similar to our windowed position encoding for coarse-to-fine optimization.
          </p>
          <p>
            <a href="https://www.albertpumarola.com/research/D-NeRF/index.html">D-NeRF</a> and <a href="https://gvv.mpi-inf.mpg.de/projects/nonrigid_nerf/">NR-NeRF</a>
            both use deformation fields to model non-rigid scenes.
          </p>
          <p>
            Some works model videos with a NeRF by directly modulating the density, such as <a href="https://video-nerf.github.io/">Video-NeRF</a>, <a href="https://www.cs.cornell.edu/~zl548/NSFF/">NSFF</a>, and <a href="https://neural-3d-video.github.io/">DyNeRF</a>
          </p>
          <p>
            There are probably many more by the time you are reading this. Check out <a href="https://dellaert.github.io/NeRF/">Frank Dellart's survey on recent NeRF papers</a>, and <a href="https://github.com/yenchenlin/awesome-NeRF">Yen-Chen Lin's curated list of NeRF papers</a>.
          </p>
        </div>
      </div>
    </div> -->
    <!--/ Concurrent Work. -->

  </div>
</section>

<section class="section">
  <div class="container is-max-desktop">
    <p>If you like the project, please show your support by <a href="https://github.com/ziplab/SN-Net">leaving a star</a> 🌟 !</p>
    </div>
</section>

<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@inproceedings{pan2023snnet,
  author    = {Pan, Zizheng and Cai, Jianfei and Zhuang, Bohan},
  title     = {Stitchable Neural Networks},
  booktitle = {CVPR},
  year      = {2023},
}</code></pre>
  </div>
</section>


<footer class="footer">
  <div class="container">
    <div class="content has-text-centered">
      <a class="icon-link"
         href="./static/videos/nerfies_paper.pdf">
        <i class="fas fa-file-pdf"></i>
      </a>
      <a class="icon-link" href="https://github.com/ziplab" class="external-link" disabled>
        <i class="fab fa-github"></i>
      </a>
    </div>
    <div class="columns is-centered">
      <div class="column is-8">
        <div class="content">
          <p>
            This website is licensed under a <a rel="license"
                                                href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
            Commons Attribution-ShareAlike 4.0 International License</a>. The website template is based on <a
            href="https://github.com/nerfies/nerfies.github.io">nerfies</a>.
          </p>
        </div>
      </div>
    </div>
  </div>
</footer>

</body>
</html>
