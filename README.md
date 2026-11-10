Tensegrity Pose Extractor — prototype

This small prototype helps normalize pose/module/configuration data from CSV or JSON files into a stable schema for downstream analysis. It does not fetch or crawl remote sites. Instead, paste or drop downloaded CSV/JSON content into the page and map fields to the standard schema.

Usage:
- Open index.html in a browser.
- Paste or drop a JSON array or CSV text.
- Map source fields to schema fields and click Normalize.
- Download normalized JSON or CSV.

Stable schema (keys): id, module_type, position_x, position_y, position_z, orientation, metadata

License: Public domain (small demo).