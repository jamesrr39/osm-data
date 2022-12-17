[osm-data]

Extracts of OSM data. Data is organised/sharded by [h3 cell](https://h3geo.org), and is encoded in a protocol buffer format. You will need to use the [protoc compiler](https://developers.google.com/protocol-buffers/docs/downloads) and the proto definitions file to generate source code to understand the data files. We provide the proto file [here](./data_files.proto).

The main branch of the repo is published to GitHub pages.

So, as well as the raw file view, you can fetch content by going to e.g. https://jamesrr39.github.io/osm-data/planet-221128/h3_representation/osm_web_data_files/resolution_3/amenity/toilets/38/3330313064666666666666666666.pb

