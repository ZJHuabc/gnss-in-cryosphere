---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

# Investigating frozen ground dynamics by using GNSS interferometric reflectometry (GNSS-IR)
Permafrost refers to the ground whose temperature remains at or below 0 °C for at least two consecutive years. On top of permafrost is the active layer undergoing seasonal freezing/thawing. The changes in the active layer and permafrost affect the hydrological, geomorphological, and ecological processes. Due to active layer freezing/thawing, the ground surface in a permafrost area is subject to uplift/subsidence. **Surface elevation changes are closely linked to the thermal and hydrological changes in the frozen ground. GNSS-IR can measure surface elevation changes. It can also estimate near-surface soil moisture content and snow depth, which also affect frozen ground dynamics.** The following slides, presented in the IGARSS 2021, shows the concept of using GNSS-IR to study permafrost and summarizes my findings.


<br/>


<div markdown="0" id="carousel" class="carousel slide" data-ride="carousel" data-interval="5000" data-pause="hover" >
    
    <ol class="carousel-indicators">
        <li data-target="#carousel" data-slide-to="0" class="active"></li>
        <li data-target="#carousel" data-slide-to="1"></li>
        <li data-target="#carousel" data-slide-to="2"></li>
        <li data-target="#carousel" data-slide-to="3"></li>
        <li data-target="#carousel" data-slide-to="4"></li>
        <li data-target="#carousel" data-slide-to="5"></li>
        <li data-target="#carousel" data-slide-to="6"></li>
        <li data-target="#carousel" data-slide-to="7"></li>
        <li data-target="#carousel" data-slide-to="8"></li>
        <li data-target="#carousel" data-slide-to="9"></li>
        <li data-target="#carousel" data-slide-to="10"></li>
        <li data-target="#carousel" data-slide-to="11"></li>
    </ol>

    
    <div class="carousel-inner" markdown="0">

        <div class="item active">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide1.png" alt="Slide 1" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide2.png" alt="Slide 2" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide3.png" alt="Slide 3" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide4.png" alt="Slide 4" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide5.png" alt="Slide 5" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide6.png" alt="Slide 6" />
        </div>       
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide7.png" alt="Slide 7" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide8.png" alt="Slide 8" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide9.png" alt="Slide 9" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide10.png" alt="Slide 10" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide11.png" alt="Slide 11" />
        </div>
        <div class="item">
            <img src="{{ site.url }}{{ site.baseurl }}/images/igarss_2021_0715/Slide12.png" alt="Slide 12" />
        </div>
    </div>
  <a class="left carousel-control" href="#carousel" role="button" data-slide="prev">
    <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="right carousel-control" href="#carousel" role="button" data-slide="next">
    <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

<br/>

<!--
<img style="float: right" src="{{ site.url }}{{ site.baseurl }}/images/geometry_gpsir_FT.jpg" width="65%">
GNSS interferometric reflectometry (GNSS-IR) is a technique utilizing the interference pattern between the direct and reflected signals to measure environmental variables, such as near-surface soil moisture content, snow depth, and water level changes (Larson, 2019). **It can be also used to measure ground surface elevation changes in permafrost areas. (Liu and Larson, 2018)** The left diagram illusrates the changes in GNSS-IR geometry in the active layer freezing/thawing processes. 

<br/>

### Suitable GNSS sites in permafrost areas in the Arctic permafrost areas

<img style="float: right" src="{{ site.url }}{{ site.baseurl }}/maps/perma_usable_gnss_tsp_calm.png" width="65%">
Nearly 200 open-data GNSS stations are continuously operating in the permafrost areas in the Northern Hemisphere. However, not all of them are suitable for GNSS-IR applications, as this technique requires the reflecting surface to be open and relatively horizontal and smooth. From the existing ones, we identified 23 suitable sites in the Arctic permafrost regions. At these usable sites, azimuth masks with open and relatively flat and horizontal areas can be determined. The suitable sites can fill some spatial gaps of the current permafrost monitoring networks. Their GNSS-IR measurements of surface elevation changes contribute to probing into frozen ground dynamics. The left map shows the distribution of the suitable GNSS sites and the Circumpolar Active Layer Monitoring and Thermal State of Permafrost sites. Go to **[Sites](./sites)** to see the details of the suitable GNSS stations. 
-->

<!--
<div markdown="0" id="usable-sites" class="col-sm-4">
    <p style="text-align:center">
        <img src="{{ site.url }}{{ site.baseurl }}/maps/suitable_gnss_sites.png" width="100%">
    </p>
    <p style="text-align:center">
        Locations of the suitable GNSS sites in the Arctic permafrost areas for GNSS-IR studies.
    </p>
    <br/>
</div>
-->


<!--
<iframe height="600px" width="100%" src="{{ site.url }}{{ site.baseurl }}/maps/sites_map.html"></iframe>
-->

<!--

References:<br/>
Larson, K. M. (2019). Unanticipated Uses of the Global Positioning System. Annual Review of Earth and Planetary Sciences, 47(1), 19–40. https://doi.org/10.1146/annurev-earth-053018-060203 
<br/>
Liu, L., & Larson, K. M. (2018). Decadal changes of surface elevation over permafrost area estimated using reflected GPS signals. The Cryosphere, 12(2), 477–489. https://doi.org/10.5194/tc-12-477-2018
<br/>
Zhang, T., Barry, R. G., Knowles, K., Ling, F., & Armstrong, R. L. (2003). Distribution of seasonally and perennially frozen ground in the Northern Hemisphere. In Proceedings of the 8th International Conference on Permafrost (pp. 1289–1294).

-->
