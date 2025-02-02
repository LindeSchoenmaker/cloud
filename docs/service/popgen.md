# PopGen

<!-- this file is autogenerated. edit popgen.json instead -->

Service to generate online virtual human population.


## VHP4Safety Selection Service

*  cloud: [http://xnet.hsl.gov.uk/Popgen/](http://xnet.hsl.gov.uk/Popgen/) []()
* Login required: No
* Implementation status: 
* TRL: 
* Type: -
* Contact:  infoline@hse.gov.uk
* API Type: [SOAP](http://xnet.hsl.gov.uk/Popgen/service.aspx)
* Demo: []()
* Categories: -
* Targeted users: -
* Relevant VHP4Safety Use case: -

## Tool specifications

* Provided by: UK Health and Safety Laboratory ([http://www.hsl.gov.uk/](http://www.hsl.gov.uk/))
* Citation: [https://doi.org/10.1007/s10928-007-9053-5](https://doi.org/10.1007/s10928-007-9053-5)
* Version: 0.3.11183.0
* License: Copyright by Bayer CropScience AG 2008
* Source Code: 
* Docker: 
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
  "@id" : "https://vhp4safety.github.io/cloud/service/popgen",
  "name": "PopGen", 
  "description": "Service to generate online virtual human population.",
  "url": "http://xnet.hsl.gov.uk/Popgen/"
}
</script>
