# interactor-obj

The weftfit adapter that reads and writes `.obj` meshes for retarget's mesh source and sink ports.

## Use

The reader and writer convert between a mesh and `.obj` with its `.mtl` materials, keeping objects, groups, materials, UVs, normals and vertex order. `ports/` holds the C ABI contracts the adapter implements, whose source is retarget.

## Build and run

Nothing builds here on its own. A consumer compiles the adapter sources into its own build.

## Licence

`LICENSE` is MIT. The reader and writer sources carry MPL-2.0 headers from the code they derive from.
