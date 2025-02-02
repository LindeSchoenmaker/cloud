# SysRev

<!-- this file is autogenerated. edit sysrev.json instead -->

Service to support literature research.


## VHP4Safety Selection Service

*  cloud: [https://sysrev.com/](https://sysrev.com/) []()
* Login required: Yes
* Implementation status: 
* TRL: 
* Type: -
* Contact: Insilica.co info@insilica.co
* API Type: REST, [R package](https://r.sysrev.com/), [Python](https://github.com/sysrev/PySysrev)
* Demo: []()
* Categories: -
* Targeted users: -
* Relevant VHP4Safety Use case: -

## Tool specifications

* Provided by:  
* Citation: [https://doi.org/10.3389/frai.2021.685298](https://doi.org/10.3389/frai.2021.685298)
* Version: 
* License: 
* Source Code: 
* Docker: 
* Bio.tools: [https://bio.tools/sysrev](https://bio.tools/sysrev)
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
  "@id" : "https://vhp4safety.github.io/cloud/service/sysrev",
  "name": "SysRev", 
  "description": "Service to support literature research.",
  "url": "https://sysrev.com/"
}
</script>
