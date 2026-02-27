# MCP DNITGeo validation

Tested `snv.get_snv_location_opt_with_point` for 12 points spaced by 7.5 km on BR-464 (MG) starting at km 330 as provided by the DNITGeo `espacializarponto` API for 2026-02-27. Each point was transformed to EPSG:31983 and matched against the nearest feature in `snv.snv_202602a` within 250 m; the interpolated kilometer remains within ≈0.1 km of the API value while returning the snapped point and fraction. Results give confidence that the local metric-based function captures the official km references even when the geometry length differs from the declared km range.
