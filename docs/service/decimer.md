# DECIMER

<!-- this file is autogenerated. edit decimer.json instead -->

Online service to extract chemical structures from PDFs and images.

![screenshot of %service%](https://raw.githubusercontent.com/VHP4Safety/cloud/main/docs/service/decimer.png "Click on the image to go to the service")
##  Service

*  cloud: [https://decimer.ai/](https://decimer.ai/) []()
* Login required: No
* Implementation status: 
* TRL: 
* Type: -
* Contact: Kohulan Rajan kohulan.rajan@uni-jena.de
* API Type: 
* Demo: []()
* Categories: -
* Targeted users: -
* Relevant VHP4Safety Use case: -

## Tool specifications

* Provided by: Steinbeck Group at the Friedrich Schiller University Jena ([https://cheminf.uni-jena.de/research/deep-learning/](https://cheminf.uni-jena.de/research/deep-learning/))
* Citation: [https://doi.org/10.1186/s13321-021-00538-8](https://doi.org/10.1186/s13321-021-00538-8)
* Version: Latest
* License: [MIT license](https://github.com/Kohulan/DECIMER-Image_Transformer/blob/master/LICENSE)
* Source Code: [https://github.com/Kohulan/DECIMER-Image_Transformer](https://github.com/Kohulan/DECIMER-Image_Transformer)
* Docker: [https://github.com/OBrink/DECIMER_Web](https://github.com/OBrink/DECIMER_Web)
* Bio.tools: 
* FAIRsharing: 
* TeSS: 
* RSD: 
* Wikipedia: 

<h3 id="tess-widget-materials-header"></h3>

<div id="tess-widget-materials-list" class="tess-widget tess-widget-list"></div>
<script>
function initTeSSWidgets() {
    var query = '';
    if (query.trim() != "") {
        TessWidget.Materials(document.getElementById('tess-widget-materials-list'),
            'SimpleList',
            {
                opts: {
                  enableSearch: false
                },
                params: {
                    pageSize: 5,
                    q: query
                }
            });
        document.getElementById('tess-widget-materials-header').innerHTML = "ELIXIR TeSS material"
    }
}
</script>
<script async="" defer="" src="https://elixirtess.github.io/TeSS_widgets/js/tess-widget-standalone.js" onload="initTeSSWidgets()"></script>

## Tool integration

- [ ] Utilises the VHP4Safety APIs to ensure that each service is accessible to our proposed interoperability layer.
- [ ] Is annotated according to the semantic interoperability layer concept using defined ontologies.
- [ ] Is containerised for easy deployment in virtual environments of VHP4Safety instances.
- [ ] Has documented scientific and technical background.
- [ ] Is deployed into the VHP4Safety development environment.
- [ ] Is deployed into the VHP4Safety production environment.
- [ ] Is listed in the VHP4Safety discovery services.
- [ ] Is listed in other central repositories like eInfraCentral, bio.tools and TeSS (ELIXIR).
- [ ] Provides legal and ethical statements on how the service can be used.

<script type="application/ld+json">
{
  "@context": "https://schema.org/",
  "@type": "SoftwareApplication",
  "http://purl.org/dc/terms/conformsTo": {
      "@type": "CreativeWork", "@id": "https://bioschemas.org/profiles/ComputationalTool/1.0-RELEASE"
  },
  "@id" : "https://vhp4safety.github.io/cloud/service/decimer",
  "name": "DECIMER", 
  "description": "Online service to extract chemical structures from PDFs and images.",
  "url": "https://decimer.ai/"
}
</script>
