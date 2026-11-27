# Nine-point proof forest: cubic-tour local reordering preprint

These parts are consecutive bytes of one XZ stream. Download all numbered parts, then run:

```sh
cat margin9.boxes.xz.part-* > margin9.boxes.xz
sha256sum -c MARGIN-XZ-SHA256.txt
```

Place the assembled file beside `reproduce.sh` after extracting [the source and certificate supplement](../cubic-tsp-cube-reordering-supplement.zip), then run `bash reproduce.sh` in that directory. This also checks the digest of the decompressed forest before replaying it.
