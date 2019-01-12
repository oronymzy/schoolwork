hero: final project discussion board post for <em><a href="../MCC-COMW100">Introduction to Web Page Creation</a></em>
...

# Some plans for my final project
For my final project, I aim to collect and describe the freely-licensed art of [SpaceX](https://en.wikipedia.org/wiki/SpaceX). The intended audience is anyone interested in spaceflight ideas. I'm using [MkDocs](https://www.mkdocs.org/) with the [MkDocs Bootstrap Theme](https://mkdocs.github.io/mkdocs-bootstrap/) to generate the site, so it will have a mostly grayscale and blue color scheme. I've already created most of the site, so here is the structure as it exists right now, generated using [tree](https://en.wikipedia.org/wiki/Tree_(command)) (source files only, not yet generated into a final site):

```
.
├── docs
│   ├── BFR.md
│   ├── CwDrgn2.md
│   ├── extra.css
│   ├── img
│   │   ├── BFR-Clouda1.jpg
│   │   ├── BFR-Clouda1-small.png
│   │   ├── BFR-Clouda2.jpg
│   │   ├── BFR-Clouda2-small.png
│   │   ├── BFR-ISSdckg.jpg
│   │   ├── BFR-ISSdckg-small.png
│   │   ├── BFR-Moonprx.jpg
│   │   ├── BFR-Moonprx-small.png
│   │   ├── BFR-Stgsep1.jpg
│   │   ├── BFR-Stgsep1-small.png
│   │   ├── BFR-Stgsep2.jpg
│   │   ├── BFR-Stgsep2-small.png
│   │   ├── BFSpfrm.jpg
│   │   ├── BFSpfrm-small.png
│   │   ├── CwDrgn2-D2aISS1.jpg
│   │   ├── CwDrgn2-D2aISS1-small.png
│   │   ├── CwDrgn2-D2aISS2.jpg
│   │   ├── CwDrgn2-D2aISS2-small.png
│   │   ├── CwDrgn2-D2nErth.jpg
│   │   ├── CwDrgn2-D2nErth-small.png
│   │   ├── DcapMrs.jpg
│   │   ├── DcapMrs-small.png
│   │   ├── ITSlnch-Earthdp.jpg
│   │   ├── ITSlnch-Earthdp-small.png
│   │   ├── ITSlnch-Edusldd.jpg
│   │   ├── ITSlnch-Edusldd-small.png
│   │   ├── ITSlnch-Eupaldd.jpg
│   │   ├── ITSlnch-Eupaldd-small.png
│   │   ├── ITSlnch-ITSblnd.jpg
│   │   ├── ITSlnch-ITSblnd-small.png
│   │   ├── ITSlnch-ITSbrls.jpg
│   │   ├── ITSlnch-ITSbrls-small.png
│   │   ├── ITSlnch-ITSlasc.jpg
│   │   ├── ITSlnch-ITSlasc-small.png
│   │   ├── ITSlnch-ITSlfto.jpg
│   │   ├── ITSlnch-ITSlfto-small.png
│   │   ├── ITSlnch-ITSlmdp.jpg
│   │   ├── ITSlnch-ITSlmdp-small.png
│   │   ├── ITSlnch-ITSlpad.jpg
│   │   ├── ITSlnch-ITSlpad-small.png
│   │   ├── ITSlnch-ITSpsld.jpg
│   │   ├── ITSlnch-ITSpsld-small.png
│   │   ├── ITSlnch-Jptrpxm.jpg
│   │   ├── ITSlnch-Jptrpxm-small.png
│   │   ├── ITSlnch-Marsaet.jpg
│   │   ├── ITSlnch-Marsaet-small.png
│   │   ├── ITSlnch-Marsavl.jpg
│   │   ├── ITSlnch-Marsavl-small.png
│   │   ├── ITSlnch-Marsldg.jpg
│   │   ├── ITSlnch-Marsldg-small.png
│   │   ├── ITSlnch-Marssfc.jpg
│   │   ├── ITSlnch-Marssfc-small.png
│   │   ├── ITSlnch-Moonpsg.jpg
│   │   ├── ITSlnch-Moonpsg-small.png
│   │   ├── ITSlnch-Prptrns.jpg
│   │   ├── ITSlnch-Prptrns-small.png
│   │   ├── ITSlnch-Strnpxm.jpg
│   │   ├── ITSlnch-Strnpxm-small.png
│   │   ├── Marstsm-OlyMons.jpg
│   │   ├── Marstsm-OlyMons-small.png
│   │   ├── Marstsm-PhoDmos.jpg
│   │   ├── Marstsm-PhoDmos-small.png
│   │   ├── Marstsm-VlsMnrs.jpg
│   │   ├── Marstsm-VlsMnrs-small.png
│   │   ├── RedDrgn-DrgnasM.jpg
│   │   ├── RedDrgn-DrgnasM-small.png
│   │   ├── RedDrgn-Drgnaty.jpg
│   │   ├── RedDrgn-Drgnaty-small.png
│   │   ├── RedDrgn-DrgnldM.jpg
│   │   ├── RedDrgn-DrgnldM-small.png
│   │   ├── RedDrgn-DrgnlM1.jpg
│   │   ├── RedDrgn-DrgnlM1-small.png
│   │   ├── RedDrgn-DrgnlM2.jpg
│   │   ├── RedDrgn-DrgnlM2-small.png
│   │   ├── RedDrgn-DrgnMrs.jpg
│   │   ├── RedDrgn-DrgnMrs-small.png
│   │   ├── RedDrgn-FHDlnch.jpg
│   │   └── RedDrgn-FHDlnch-small.png
│   ├── ITSlnch.md
│   ├── Marstsm.md
│   ├── README.md
│   └── RedDrgn.md
└── mkdocs.yml
```

`README.md` is the homepage. It includes an example image, an overview of SpaceX, and the entire site's licensing information. Most pages will also include information from Wikipedia introductions. The `img` directory contains the art images, each one with a thumbnail version suffixed with `-small`. `BFR.md`, `CwDrgn2.md`, `ITSlnch.md`, `Marstsm.md`, and `RedDrgn.md` will cover *[Big Falcon Rocket](https://en.wikipedia.org/wiki/BFR_(rocket))*, *[Crew Dragon 2](https://en.wikipedia.org/wiki/Dragon_2)*, *[Interplanetary Transport System launch vehicle](https://en.wikipedia.org/wiki/ITS_launch_vehicle)*, *Mars tourism posters*, and *[Red Dragon](https://en.wikipedia.org/wiki/SpaceX_Red_Dragon)*, respectively.
