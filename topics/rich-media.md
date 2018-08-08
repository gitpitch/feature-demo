## Math Formulas Slides
@css[tip](Press the Space or Down key for a live demo.)

@fa[arrow-down]

@snap[south doclink]
See the [GitPitch Math Formulas Docs](https://gitpitch.com/docs/rich-media-features/math-formulas) for further details.
@snapend

+++
@title[Beautiful Math]

#### Beautiful Math Rendered Beautifully

<br>

Use *TeX*, *LaTeX* and *MathML* markup   
powered by [MathJax](https://www.mathjax.org).

+++
@title[Sample]

`$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$`

+++
@title[Sample]

`\begin{align}
\dot{x} & = \sigma(y-x) \\
\dot{y} & = \rho x - y - xz \\
\dot{z} & = -\beta z + xy
\end{align}`

+++
@title[Sample]

##### The Cauchy-Schwarz Inequality

`\[
\left( \sum_{k=1}^n a_k b_k \right)^{\!\!2} \leq
 \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
\]`

+++
@title[Inline Sample]

##### In-line Mathematics

This expression `\(\sqrt{3x-1}+(1+x)^2\)` is an example of an inline equation.

---

## Chart Slides
@css[tip](Press the Space or Down key for a live demo.)

@fa[arrow-down]

@snap[south doclink]
See the [GitPitch Charts Docs](https://gitpitch.com/docs/rich-media-features/charts) for further details.
@snapend

+++
@title[Chart Types]

#### Chart Data Rendered Beautifully

<br>

Use *Bar*, *Line*, *Area*, and *Scatter* charts among many other chart types directly within your markdown, all powered by [Chart.js](http://www.chartjs.org).

+++
@title[Sample Line Chart]

<canvas data-chart="line">
<!--
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets": [
   {
    "data":[65,59,80,81,56,55,40],
    "label":"My first dataset","backgroundColor":"rgba(20,220,220,.8)"
   },
   {
    "data":[28,48,40,19,86,27,90],
    "label":"My second dataset","backgroundColor":"rgba(220,120,120,.8)"
   }
  ]
 },
 "options": { "responsive": "true" }
}
-->
</canvas>

+++
@title[Sample Bar Chart]

<canvas class="stretch" data-chart="horizontalBar">
<!--
{
 "data" : {
  "labels" : ["Grapefruit", "Orange", "Kiwi",
    "Blackberry", "Banana",
    "Blueberry"],
  "datasets" : [{
    "data": [48, 26, 59, 39, 21, 74],
    "backgroundColor": "#e49436",
    "borderColor": "#e49436"
  }]
  },
  "options": {
    "title": {
      "display": true,
      "text": "The most delicious fruit?",
      "fontColor": "gray",
      "fontSize": 20
    },
    "legend": {
      "display": false
    },
    "scales": {
      "xAxes": [{
        "ticks": {
            "beginAtZero": true,
            "max": 80,
            "stepSize": 10,
            "fontColor": "gray"
        },
        "scaleLabel": {
          "display": true,
          "labelString": "Respondents",
          "fontColor": "gray"
        }
      }],
      "yAxes": [{
        "ticks": {
            "fontColor": "gray"
        }
      }]
    }
  }
}
-->
</canvas>

---
@title[Embed Video]
## Video Slides
## [ Inline ]
@css[tip](Press the Space or Down key for a live demo.)

@fa[arrow-down]

@snap[south doclink]
See the [GitPitch Inline Video Docs](https://gitpitch.com/docs/rich-media-features/inline-videos) for further details.
@snapend

+++
@title[YouTube, etc]

#### Bring Your Presentations Alive

<br>

Embed *YouTube*, *Vimeo*, *MP4* and *WebM*   
inline on any slide.

+++
@title[Fresh Guacamole]

![YouTube Video](https://www.youtube.com/embed/dNJdJIwCF_Y)

+++
@title[Gravity]

![Vimeo Video](https://player.vimeo.com/video/125471012)

+++
@title[Big Buck Bunny]

![MP4 Video](http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4)

---
@title[Background Videos]

## Video Slides
## [ Background ]
@css[tip](Press the Space or Down key for a live demo.)

@fa[arrow-down]

@snap[south doclink]
See the [GitPitch Background Video Docs](https://gitpitch.com/docs/rich-media-features/background-videos) for further details.
@snapend

+++
@title[Viewer Experience]

#### Maximize The Viewer Experience

<br>

Go fullscreen with *MP4* and *WebM* videos.

+++?video=http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4
@title[Big Buck Bunny]

