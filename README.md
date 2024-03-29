# danny
<html lang="en" data-is-home="false" data-is-mobile="false" data-supports-vr="false" data-supports-touch="false" data-site-base-url="https://aframe.io" data-site-root-path="/" data-site-home-url="https://aframe.io/" data-lib-home-url="https://aframe.io/" data-lib-examples-url="https://aframe.io/aframe/examples" data-title="{title} | A-Frame" data-is-spa="false" data-ga-id="UA-24056643-4" data-aframe-version="0.4.0" data-docs-version="0.4.0" data-is-android="false" data-is-ios="false" data-supports-vr-legacy="false" data-supports-webvrplus="false" class="gr__aframe_io"><head>
    <title>Spheres &amp; Fog – A-Frame</title>
    

<script async="" src="//www.google-analytics.com/analytics.js"></script><script>
  var host = window.location.protocol + '//' + window.location.hostname;
  if (window.location.protocol === 'http:' &&
      window.location.hostname === 'https://aframe.io') {
    window.location.href = 'https:' + window.location.href.substring(6);
  }
</script>


    <meta charset="utf-8">
    <!-- Don't index old documentation pages. -->
    <meta name="robots" content="all">
    <meta name="description" content="A web framework for building virtual reality experiences. Make WebVR with HTML and the Entity-Component ecosystem. Works across HTC Vive, Oculus Rift, desktop, and mobile platforms.">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <link rel="canonical" href="https://aframe.io">
    <link href="https://fonts.googleapis.com/css?family=Fira+Sans:300,400,600" rel="stylesheet">
    <meta property="fb:app_id" content="1535794316743373">
    <meta property="og:title" content="Spheres &amp; Fog – A-Frame">
    <meta property="og:site_name" content="A-Frame">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://aframe.io">
    <meta property="og:description" content="A web framework for building virtual reality experiences. Make WebVR with HTML and the Entity-Component ecosystem. Works across HTC Vive, Oculus Rift, desktop, and mobile platforms.">
    <meta property="og:image" content="http://aframe.io/images/card.jpg?v2">
    <meta property="og:image:secure_url" content="https://aframe.io/images/card.jpg?v2">
    <meta name="twitter:card" content="summary">
    <meta name="twitter:site" content="@aframevr">
    <meta name="twitter:creator" content="@aframevr">
    <meta name="twitter:title" content="Spheres &amp; Fog – A-Frame">
    <meta name="twitter:description" content="A web framework for building virtual reality experiences. Make WebVR with HTML and the Entity-Component ecosystem. Works across HTC Vive, Oculus Rift, desktop, and mobile platforms.">
    <meta name="twitter:image" content="https://aframe.io/images/card.jpg?v2">
    <meta name="mobile-web-app-capable" content="yes">
    <meta name="theme-color" content="black">
    <link rel="icon" sizes="192x192" href="https://aframe.io/images/aframe-logo-192.png">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <link rel="apple-touch-icon" href="https://aframe.io/images/aframe-logo-152.png">
    <link rel="alternate" type="application/rss+xml" title="Feed" href="https://aframe.io/feed.xml">
    
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-24056643-4', 'auto');
  ga('send', 'pageview');
</script>



    
      <script src="/js/compat.js"></script>
    

    
      <link rel="stylesheet" href="/css/index.css">
      
        <link rel="stylesheet" href="/css/examples.css">
      
    

    
  </head>

  <body data-page-layout="" data-page-type="examples" data-gr-c-s-loaded="true">
    <main id="main" class="main">

<!-- Homepage examples bar. -->
<aside class="sidebar">
  <div class="sidebar__wrap">
    <div class="sidebar__wrap__inner">

      <!-- Wordmark. -->
      <header id="header" class="header">
        <a id="logo" class="logo borderless-links" href="/">
          <span class="logo__wordmark">A-Frame</span>
        </a>
      </header>

      <!-- Get Started for Mobile. -->
      <a href="/docs/" class="mobile-get-started nav-link get-started">
        Get Started
      </a>

      <!-- Examples. -->
      <div class="list examples-list">
        <h2 class="page-title">Examples</h2>
        <ul id="examplesSubnav" class="subnav examples-subnav borderless-links">
          
            
            <li data-current="false" data-supports-mobile="true" data-example-url="/examples/showcase/helloworld/" data-scene-url="https://aframe.io/aframe/examples/boilerplate/hello-world/" data-slug="helloworld" data-idx="0" class="example-item subnav-item">
              <a href="/examples/showcase/helloworld/" class="subnav-link">
                <span class="sidebar__link__text">Hello WebVR</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="false" data-example-url="/examples/showcase/hello-metaverse/" data-scene-url="https://ngokevin.github.io/kframe/components/text/examples/vaporwave/" data-slug="hello-metaverse" data-idx="1" class="example-item subnav-item">
              <a href="/examples/showcase/hello-metaverse/" class="subnav-link">
                <span class="sidebar__link__text">Hello Metaverse</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="true" data-example-url="/examples/showcase/sky/" data-scene-url="https://aframe.io/aframe/examples/boilerplate/panorama/" data-slug="sky" data-idx="2" class="example-item subnav-item">
              <a href="/examples/showcase/sky/" class="subnav-link">
                <span class="sidebar__link__text">360° Image</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="true" data-example-url="/examples/showcase/360-image-gallery/" data-scene-url="https://aframe.io/360-image-gallery-boilerplate/" data-slug="360-image-gallery" data-idx="3" class="example-item subnav-item">
              <a href="/examples/showcase/360-image-gallery/" class="subnav-link">
                <span class="sidebar__link__text">360° Image Gallery</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="false" data-example-url="/examples/showcase/videosphere/" data-scene-url="https://aframe.io/aframe/examples/boilerplate/360-video/" data-slug="videosphere" data-idx="4" class="example-item subnav-item">
              <a href="/examples/showcase/videosphere/" class="subnav-link">
                <span class="sidebar__link__text">360° Video</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="true" data-example-url="/examples/showcase/anime-UI/" data-scene-url="https://aframe.io/aframe/examples/showcase/anime-UI/" data-slug="anime-UI" data-idx="5" class="example-item subnav-item">
              <a href="/examples/showcase/anime-UI/" class="subnav-link">
                <span class="sidebar__link__text">Anime UI</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="false" data-example-url="/examples/showcase/audio-visualization/" data-scene-url="https://ngokevin.github.io/kframe/components/audioanalyser/examples/showcase/" data-slug="audio-visualization" data-idx="6" class="example-item subnav-item">
              <a href="/examples/showcase/audio-visualization/" class="subnav-link">
                <span class="sidebar__link__text">Audio Visualization</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="false" data-example-url="/examples/showcase/shopping/" data-scene-url="https://shopifyvr.myshopify.com/pages/virtual-reality" data-slug="shopping" data-idx="7" class="example-item subnav-item">
              <a href="/examples/showcase/shopping/" class="subnav-link">
                <span class="sidebar__link__text">ShopifyVR</span>
                
              </a>
            </li>
          
            
            <li data-current="true" data-supports-mobile="true" data-example-url="/examples/showcase/spheres-and-fog/" data-scene-url="https://aframe.io/aframe/examples/showcase/spheres-and-fog/" data-slug="spheres-and-fog" data-idx="8" class="example-item subnav-item current">
              <a href="/examples/showcase/spheres-and-fog/" class="subnav-link current">
                <span class="sidebar__link__text">Spheres &amp; Fog</span>
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="false" data-example-url="/examples/showcase/tracked-controllers/" data-scene-url="https://aframe.io/aframe/examples/showcase/tracked-controls/" data-slug="tracked-controllers" data-idx="9" class="example-item subnav-item">
              <a href="/examples/showcase/tracked-controllers/" class="subnav-link">
                <span class="sidebar__link__text">Tracked Controllers</span>
                
                  <img class="example-tracked-controllers" src="/images/controllers.png" title="This example supports or requires tracked controllers.">
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="true" data-example-url="/examples/showcase/a-blast/" data-scene-url="https://aframe.io/a-blast/" data-slug="a-blast" data-idx="10" class="example-item subnav-item">
              <a href="/examples/showcase/a-blast/" class="subnav-link">
                <span class="sidebar__link__text">A-Blast</span>
                
                  <img class="example-tracked-controllers" src="/images/controllers.png" title="This example supports or requires tracked controllers.">
                
              </a>
            </li>
          
            
            <li data-current="false" data-supports-mobile="true" data-example-url="/examples/showcase/a-painter/" data-scene-url="https://aframe.io/a-painter/?url=https://ucarecdn.com/962b242b-87a9-422c-b730-febdc470f203/" data-slug="a-painter" data-idx="11" class="example-item subnav-item">
              <a href="/examples/showcase/a-painter/" class="subnav-link">
                <span class="sidebar__link__text">A-Painter</span>
                
                  <img class="example-tracked-controllers" src="/images/controllers.png" title="This example supports or requires tracked controllers.">
                
              </a>
            </li>
          
        </ul>

        <!-- Navigation arrows. -->
        <nav class="example-nav c">
          <a id="examplePrev" class="example-nav-link example-nav-prev" href="#">← <span>Previous</span></a>
          <a id="exampleNext" class="example-nav-link example-nav-next float-right" href="#"><span>Next</span> →</a>
        </nav>
      </div>
    </div>
  </div>
</aside>


<div class="content content--examples">
  <div class="content--body">
    <!-- Example. -->
    <iframe id="exampleIframe" class="example__iframe" width="100%" height="100%" allowfullscreen="yes" scrolling="no" allowvr="yes" src="https://aframe.io/aframe/examples/showcase/spheres-and-fog/"></iframe>

    <!-- Actions. -->
    <div class="example__controls">
      
        <a id="exampleInspector" class="btn" rel="nofollow" title="Or open with `<ctrl> + <alt> + i`.">Visual Inspector</a>
      
      
        <a id="exampleViewSource" class="btn" href="https://github.com/aframevr/aframe/blob/v0.4.0/examples/showcase/spheres-and-fog/index.html" target="_blank" title="View the HTML on GitHub">View Source</a>
      
    </div>
  </div>
</div>
</main>

    
      <script src="/js/common.js"></script>
      <script src="/js/ga.js"></script>
      
        <script src="/js/examples.js"></script>
      
      
        <script src="/js/docs.js"></script>
      
    

    
  

</body></html>
