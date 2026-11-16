### mac0S

```shell
docker run -it --rm \
-v "$(pwd):/data" \
ghcr.io/systemed/tilemaker:master \
/data/shizuoka.osm.pbf \
--output /data/shizuoka.pmtiles
```

### Windows
```shell
docker run -it --rm ^
-v "%CD%:/data" ^
ghcr.io/systemed/tilemaker:master ^
/data/shizuoka.osm.pbf ^
--output /data/shizuoka.pmtiles
```