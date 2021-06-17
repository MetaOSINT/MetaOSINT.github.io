---
layout: default
title: "Interactive Chart"
permalink: /chart/
---

   <style>
    .container{  
      text-align: center;  
    }
    .container2{  
      font-size: 16px;
      color: #8b786f;
      font-family: 'Roboto', sans-serif;
    }
    .container3{  
      text-align: center;
    }
    .button {
      border: 2px solid #8b786f;
      border-radius: 8px;
      padding: 5px 15px;
      background-color: #f5f5f5;
      color: #8b786f;
      font-size: 23px;
      cursor: pointer;
      font-family: 'Open Sans', sans-serif;
    }
    .button2 {
      border: 2px solid #8b786f;
      border-radius: 8px;
      padding: 5px 15px;
      background-color: #dcdcdc;
      color: #8b786f;
      font-size: 23px;
      cursor: pointer;
      font-family: 'Open Sans', sans-serif;
    }
  </style>

  <body style="margin-right:95px;margin-left:95px">
  
  <div class="container3">

  <a href="https://metaosint.github.io/"><img src="https://raw.githubusercontent.com/MetaOSINT/MetaOSINT.github.io/main/MetaOSINT_logo.PNG" alt="MetaOSINT_logo" width="315" height="385" style="border:5px solid #ece4d8;box-shadow: 0px 4px 0px #ece4d8"></a>
  
   </div>
   
    <div class="container">  
      
    <a href="https://metaosint.github.io/" class="button"><strong>Home</strong></a>
    <a href="https://metaosint.github.io/chart/" class="button2"><strong>MO Chart</strong></a>
    <a href="https://metaosint.github.io/table/" class="button"><strong>Full Results Table</strong></a>
    <a href="https://metaosint.github.io/faq/" class="button"><strong>FAQ</strong></a>
    <a href="https://metaosint.github.io/thanks/" class="button"><strong>Acknowledgments</strong></a>
       
    </div>

    <p style="color:#8b786f;font-size:18px;font-family: 'Roboto', sans-serif"><br>Consider bookmarking this page to return directly to the chart next time.</p>
        
    <p style="color:#8b786f;font-size:18px;font-family: 'Roboto', sans-serif"><strong>Navigating MO:</strong> It's pretty simple - follow the guidance at the top of the bubble chart below to zoom in and out, and - if you choose to - navigate directly to specific tools & resources. <strong>Practice safe OSINT!</strong> The lowest-level bubble labels contain live resource links and should be clicked with discretion. (Pro Tip: Inspect the Privacy / Operational Security bubble for resources on the topic!) <strong>Mo' OSINT? No problem!</strong></p>
      
   <script type="module">
   import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
   import define from "https://api.observablehq.com/@metaosint/metaosint.js?v=3";
   new Runtime().module(define, name => {
     if (name === "chart") return new Inspector(document.querySelector("#observablehq-chart-96fbc5e5"));
   });
   </script>
   
  </body>

<div id="observablehq-chart-96fbc5e5"></div>

<p style="color:#8b786f;font-size:13px;font-family: 'Roboto', sans-serif"><a href="https://github.com/MetaOSINT/MetaOSINT.github.io">Inspect MO's inelegant site code</a>
<br><a href="https://twitter.com/IntelScott">Don't @ me</a> (Just kidding, please feel free. MO improvement suggestions and feedback are also welcome!)
<br>Not into Twitter? I hear you. Get in touch <a href="mailto:MetaOSINT@protonmail.com">another way</a>.</p>

  <body style="margin-right:95px;margin-left:95px">

  <img src="https://raw.githubusercontent.com/MetaOSINT/MetaOSINT.github.io/main/header_left.PNG" alt="MetaOSINT_header_left" width="387" height="173" style="border:5px solid #ece4d8;box-shadow: 0px 4px 0px #ece4d8" align="left">

  <img src="https://raw.githubusercontent.com/MetaOSINT/MetaOSINT.github.io/main/header_right.PNG" alt="MetaOSINT_header_right" width="530" height="167" style="border:5px solid #ece4d8;box-shadow: 0px 4px 0px #ece4d8" align="right">
   
    </body>
