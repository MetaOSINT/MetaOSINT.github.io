---
layout: default
title: Visualize Top OSINT Resources
---

 <img src="https://raw.githubusercontent.com/MetaOSINT/MetaOSINT.github.io/main/header.PNG" alt="MetaOSINT_Header" width="425" height="285" style="border:5px solid #ece4d8;box-shadow: 0px 4px 0px #ece4d8">
 
  <body>

    <p style="color:#8b786f;font-size:21px;font-family: 'Open Sans', sans-serif">Mo' OSINT, mo' problems? MetaOSINT ("MO") is here to help.</p>  

    <p style="color:#8b786f;font-size:16px;font-family: 'Open Sans', sans-serif">MO visualizes top OSINT sources - based on citations on dozens of OSINT tool & resource lists - saving valuable time during OSINT investigations.</p>
 
    <p style="color:#8b786f;font-size:16px;font-family: 'Open Sans', sans-serif">MO analyzed a staggering 17,000 source links appearing on nearly 30 lists of OSINT tools & resources. A large amount of overlap was quickly identified - this is what MO visualizes, calling out the "top" resources based on number of citations. In total, more than 11,000 unique OSINT resources were identified on these 28 lists alone. MO ultimately provides and visualizes the top of these resources - the 4,817 resources cited multiple times across these lists.</p>  

    <p style="color:#8b786f;font-size:16px;font-family: 'Open Sans', sans-serif">MO was conceived by a former OSINT analyst, but entered existence simply as a coding project. If you benefited from this tool, please consider a small donation to MO's favorite charity! </p>  


    <script type="module">
    import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
    import define from "https://api.observablehq.com/@metaosint/metaosint.js?v=3";
    new Runtime().module(define, name => {
      if (name === "chart") return new Inspector(document.querySelector("#observablehq-chart-386f21a4"));
    });
    </script>

  </body>

<div id="observablehq-chart-386f21a4"></div>
<p>Credit: <a href="https://observablehq.com/@metaosint/metaosint">MetaOSINT by metaosint</a></p>
