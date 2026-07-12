# weftfit/obj

Wavefront **OBJ** source+sink **adapter** for weftfit — implements `retarget`'s
`mesh_source` / `mesh_sink` ports over `.obj` (+ `.mtl` groups/materials).

- **`adapters/io/`** — `OBJReader` / `OBJWriter` / `OBJData`: mesh ⇄ OBJ,
  preserving objects/groups, materials, UVs, normals and vertex order.
- **`ports/`** — the contracts this adapter implements.

OBJ is the import-only fallback / parity baseline for the OpenUSD path (weftfit/stage).
