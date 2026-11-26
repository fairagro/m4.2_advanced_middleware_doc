# FAIRagro Advanced Middleware — ecosystem hub {#ecosystem}

Harvester harvests an RDI catalog; SQL-to-ARC runs inside another RDI against its SQL database. Both upload RO-Crate ARCs to the **Middleware API**, which stores them and publishes to **DataHUB**; **SearchHUB** and **SciWin** consume in parallel.

- The Middleware API does not harvest; it accepts uploads, stores ARCs, and publishes.
- The API is the only write path into DataHUB for this family.
- SearchHUB and SciWin are external consumers; they are not implemented here.
- Box clicks stay on this map; open every standalone diagram from the catalog below.

@answer scope="ecosystem map · conceptual · SearchHUB/SciWin external · full diagram catalog via HTTPS links"
@meta locale=en quality_profile=showcase

## How do the pieces connect? {#map}

@diagram architecture id=ecosystem-map source=ecosystem-overview.architecture.json title="FAIRagro Advanced Middleware — ecosystem"

## Which diagrams are available? {#catalog}

| Diagram | Component | Full page |
| --- | --- | --- |
| Ecosystem overview | Family | [Open ecosystem overview](https://fairagro.github.io/m4.2_advanced_middleware_doc/ecosystem-overview.html) |
| System overview | Middleware API | [Open system overview](https://fairagro.github.io/m4.2_advanced_middleware_doc/overview.html) |
| Harvest ingest sequence | Middleware API | [Open harvest ingest](https://fairagro.github.io/m4.2_advanced_middleware_doc/ingest-sequence.html) |
| API process internals | Middleware API | [Open API process](https://fairagro.github.io/m4.2_advanced_middleware_doc/api-detail.html) |
| Worker process internals | Middleware API | [Open worker process](https://fairagro.github.io/m4.2_advanced_middleware_doc/worker-detail.html) |
| Harvester overview | Harvester | [Open Harvester overview](https://fairagro.github.io/m4.2_advanced_middleware_doc/harvester-overview.html) |
| Harvester pipeline | Harvester | [Open Harvester pipeline](https://fairagro.github.io/m4.2_advanced_middleware_doc/harvester-pipeline.html) |
| SQL-to-ARC overview | SQL-to-ARC | [Open SQL-to-ARC overview](https://fairagro.github.io/m4.2_advanced_middleware_doc/sql-to-arc-overview.html) |
| SQL-to-ARC data flow | SQL-to-ARC | [Open SQL-to-ARC data flow](https://fairagro.github.io/m4.2_advanced_middleware_doc/sql-to-arc-pipeline.html) |
| SQL-to-ARC database views | SQL-to-ARC | [Open SQL-to-ARC views](https://fairagro.github.io/m4.2_advanced_middleware_doc/sql-to-arc-views.html) |
