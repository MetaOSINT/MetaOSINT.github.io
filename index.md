---
layout: default
title: Top OSINT Resources Visualization
---

  <body style="margin-right:125px;margin-left:125px">
  
    <img src="https://raw.githubusercontent.com/MetaOSINT/MetaOSINT.github.io/main/header_left.PNG" alt="MetaOSINT_header_right" width="464" height="200" style="border:5px solid #ece4d8;box-shadow: 0px 4px 0px #ece4d8" align="left">

    <img src="https://raw.githubusercontent.com/MetaOSINT/MetaOSINT.github.io/main/header_right.PNG" alt="MetaOSINT_header_right" width="556" height="200" style="border:5px solid #ece4d8;box-shadow: 0px 4px 0px #ece4d8" align="right">
 
    <p style="color:#8b786f;font-size:21px;text-align:center;font-family: 'Roboto', sans-serif">
    <br>
    <br>
    <br>
    <br><strong>Mo' OSINT, mo' problems?</strong>
    <br>MetaOSINT ("MO") is here to help.</p>  

    <p style="color:#8b786f;font-size:16px;font-family: 'Roboto', sans-serif">MO visualizes top OSINT sources - based on tens of thousands of citations on dozens of OSINT tool & resource lists - saving valuable time during OSINT investigations.
    <br>
    <br>MO analyzed a staggering <strong>17,000 source links</strong> appearing on nearly 30 lists of OSINT tools & resources. MO visualizes the overlap among these source lists, highlighting the "top" resources based on total number of shared citations. In total, more than <strong>11,000 unique OSINT resources were identified</strong> on the 28 evaluated lists alone. MO ultimately considers the top among these resources - the <strong>4,817 resources</strong> cited multiple times across these lists.
    <br>
    <br>We expect MO will have two primary uses:
    <br>
    <br>(Bonus!) #3:
    <br>
    <br>MO was conceived by an OSINT practitioner, but entered existence as an excuse to practice coding during the COVID-19 pandemic. If you benefited from this tool, please consider a small donation to MO's charity of choice!</p>

    <script type="module">
    import {Runtime, Inspector} from "https://cdn.jsdelivr.net/npm/@observablehq/runtime@4/dist/runtime.js";
    import define from "https://api.observablehq.com/@metaosint/metaosint.js?v=3";
    new Runtime().module(define, name => {
      if (name === "chart") return new Inspector(document.querySelector("#observablehq-chart-ed16bb5c"));
    });
    </script>

  </body>

<div id="observablehq-chart-ed16bb5c"></div>
<p>Credit: <a href="https://observablehq.com/@metaosint/metaosint">MetaOSINT by metaosint</a></p>
