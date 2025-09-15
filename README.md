<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <!-- Meta tags for social media banners, these should be filled in appropriatly as they are your "business card" -->
  <!-- Replace the content tag with appropriate information -->
  <meta name="description" content="DESCRIPTION META TAG">
  <meta property="og:title" content="SOCIAL MEDIA TITLE TAG"/>
  <meta property="og:description" content="SOCIAL MEDIA DESCRIPTION TAG TAG"/>
  <meta property="og:url" content="URL OF THE WEBSITE"/>
  <!-- Path to banner image, should be in the path listed below. Optimal dimenssions are 1200X630-->
  <meta property="og:image" content="static/image/your_banner_image.png" />
  <meta property="og:image:width" content="1200"/>
  <meta property="og:image:height" content="630"/>


  <meta name="twitter:title" content="TWITTER BANNER TITLE META TAG">
  <meta name="twitter:description" content="TWITTER BANNER DESCRIPTION META TAG">
  <!-- Path to banner image, should be in the path listed below. Optimal dimenssions are 1200X600-->
  <meta name="twitter:image" content="static/images/your_twitter_banner_image.png">
  <meta name="twitter:card" content="summary_large_image">
  <!-- Keywords for your paper to be indexed by-->
  <meta name="keywords" content="KEYWORDS SHOULD BE PLACED HERE">
  <meta name="viewport" content="width=device-width, initial-scale=1">


  <title>Follow-Bench: A Unified Motion Planning Benchmark for Socially-Aware Robot Person Following</title>
  <link rel="icon" type="image/x-icon" href="static/images/favicon.ico">
  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro"
  rel="stylesheet">

  <link rel="stylesheet" href="static/css/bulma.min.css">
  <link rel="stylesheet" href="static/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="static/css/bulma-slider.min.css">
  <link rel="stylesheet" href="static/css/fontawesome.all.min.css">
  <link rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="static/css/index.css">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
  <script defer src="static/js/fontawesome.all.min.js"></script>
  <script src="static/js/bulma-carousel.min.js"></script>
  <script src="static/js/bulma-slider.min.js"></script>
  <script src="static/js/index.js"></script>
</head>
<body>


  <section class="hero">
    <div class="hero-body">
      <div class="container is-max-desktop">
        <div class="columns is-centered">
          <div class="column has-text-centered" style="max-width: 150%; width: 100%; padding-left: 0; padding-right: 0;">
            <h1 class="title is-1 publication-title" style="width: 100%; word-wrap: break-word;">Follow-Bench: A Unified Motion Planning Benchmark for Socially-Aware Robot Person Following
            </h1>
            <!-- <div class="is-size-5 publication-authors">
              <span class="author-block">
                <a href="https://medlartea.github.io/" target="_blank">Hanjing Ye</a><sup>1</sup>,</span>
              <span class="author-block">
                <a href="https://scholar.google.com/citations?user=O0M3wWQAAAAJ&hl=en" target="_blank">Yu Zhan</a><sup>1</sup>,</span>
              <span class="author-block">
                <a href="https://github.com/Situ-Weixi" target="_blank">Weixi Situ</a><sup>1</sup>,</span>
              <span class="author-block">
                <a href="https://scholar.google.com/citations?user=xffeKl8AAAAJ&hl=en" target="_blank">Guangcheng Chen</a><sup>1</sup>,</span>
              <span class="author-block">
                <a href="https://jingwenyust.github.io/" target="_blank">Jingwen Yu</a><sup>1,4</sup>,</span>
              <span class="author-block">
                <a href="https://scholar.google.com/citations?user=eEt3G0oAAAAJ&hl=zh-CN" target="_blank">Ziqi Zhao</a><sup>3</sup>,</span>
              <span class="author-block">
                <a href="https://scholar.google.com/citations?user=3Y9wVfMOtP4C&hl=en" target="_blank">Kuanqi Cai</a><sup>2</sup>,</span>
              <span class="author-block">
                  <a href="https://scholar.google.com/citations?user=1hKOgRoAAAAJ&hl=en" target="_blank">Arash Ajoudani</a><sup>2</sup>,</span>
              <span class="author-block">
                <a href="https://scholar.google.com/citations?user=J7UkpAIAAAAJ&hl=en" target="_blank">Hong Zhang</a><sup>1</sup></span>
            </div>
                  <div class="is-size-5 publication-authors">
                    <span class="author-block"><sup>1</sup>RCV Lab, Southern University of Science and Technology<br></span>
                  </div>
                  <div class="is-size-5 publication-authors">
                    <span class="author-block"><sup>2</sup>HRI<sup><i>2</i></sup> Lab, Italian Institute of Technology<br></span>
                  </div>
                  <div class="is-size-5 publication-authors">
                    <span class="author-block"><sup>3</sup>RPAI Lab, Southern University of Science and Technology<br></span>
                  </div>
                  <div class="is-size-5 publication-authors">
                    <span class="author-block"><sup>4</sup>Chen Kar-Shun RI, Hong Kong University of Science and Technology<br></span>
                  </div> -->
                  

                  <div class="column has-text-centered">
                    <div class="publication-links">
                      <!-- Arxiv PDF link -->
                      <!-- <span class="link-block">
                        <a href="http://arxiv.org/abs/2505.07446" target="_blank"
                        class="external-link button is-normal is-rounded is-dark">
                        <span class="icon">
                          <i class="ai ai-arxiv"></i>
                        </span>
                        <span>arXiv</span>
                      </a>
                    </span> -->

                    <!-- Video -->
                    <!-- <span class="link-block">
                      <a href="https://youtu.be/LLZT9cEa6K0" target="_blank"
                      class="external-link button is-normal is-rounded is-dark">
                      <span class="icon">
                        <i class="fab fa-youtube"></i>
                      </span>
                      <span>Video</span>
                    </a>
                  </span> -->

                <!-- Github link -->
                <span class="link-block">
                  <a href="" target="_blank"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Code Coming Soon</span>
                  </a>
                </span>

                <!-- Github link -->
                <!-- <span class="link-block">
                  <a href="" target="_blank"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                      <i class="fas fa-home"></i>
                    </span>
                    <span>Dataset (TODO)</span>
                  </a>
                </span> -->

                <!-- ArXiv abstract Link -->
                <!-- <span class="link-block">
                  <a href="https://arxiv.org/abs/<ARXIV PAPER ID>" target="_blank"
                  class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                    <i class="ai ai-arxiv"></i>
                  </span>
                  <span>arXiv</span>
                </a>
              </span> -->
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>


<!-- Teaser image -->
<!-- <section class="hero teaser">
  <div class="hero-body">
    <div class="container">
      <img src="static/images/cover.png" alt="MY ALT TEXT" style="width: 100%; max-width: 1600px; height: auto;"/>
      <h2 class="subtitle has-text-centered">
        xxx
      </h2>
    </div>
  </div>
</section> -->
<!-- End teaser image -->

<!-- Teaser video-->
<!-- <section class="hero teaser">
  <div class="container is-max-desktop">
    <div class="hero-body">
      <video poster="" id="tree" autoplay controls muted loop height="100%">
        <source src="static/videos/teaser_video.mp4"
        type="video/mp4">
      </video>
    </div>
  </div>
</section> -->
<!-- End teaser video -->

<!-- Paper abstract -->
<section class="section hero is-light">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3">Abstract</h2>        <div class="content has-text-justified">
          <p>
            Robot person following (RPF)---mobile robots that follow and assist a specific person---has emerging applications in personal assistance, security patrols, eldercare, and logistics. To be effective, such robots must accompany the target while ensuring both safety and comfort for the target and surrounding people. In this work, we present the first end-to-end study of RPF, which (i) surveys representative scenarios, motion-planning methods, and evaluation metrics with a focus on safety and comfort; (ii) introduces Follow-Bench, a unified benchmark that simulates diverse scenarios, including various target trajectory patters, dynamic-crowd patterns, and topographical variations; and (iii) re-implements six popular RPF planners, ensuring that both safety and comfort are systematically considered. Moreover, we evaluate the two highest-performing planners from our benchmark on a differential-drive robot to provide insights into real-world deployment. Extensive simulation and real-world experiments provide quantitative insights into the safety-comfort trade-offs of existing planners, while revealing open challenges and future research directions.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- End paper abstract -->

<!-- Video carousel -->

<!-- End video carousel -->

  <footer class="footer">
  <div class="container">
    <div class="columns is-centered">
      <div class="column is-8">
        <div class="content">

          <p>
            This page was built using the <a href="https://github.com/eliahuhorwitz/Academic-project-page-template" target="_blank">Academic Project Page Template</a> which was adopted from the <a href="https://nerfies.github.io" target="_blank">Nerfies</a> project page.
            You are free to borrow the source code of this website, we just ask that you link back to this page in the footer. <br> This website is licensed under a <a rel="license"  href="http://creativecommons.org/licenses/by-sa/4.0/" target="_blank">Creative
            Commons Attribution-ShareAlike 4.0 International License</a>.
          </p>

        </div>
      </div>
    </div>
  </div>
</footer>

<!-- Statcounter tracking code -->
  
<!-- You can add a tracker to track page visits by creating an account at statcounter.com -->

    <!-- End of Statcounter Code -->

  </body>
  </html>
