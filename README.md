# ODM Meshing Module

This is a part of the larger [OpenDroneMap](https://opendronemap.org/) project and falls under the same license.

## Build

```
mkdir build
cd build
cmake -DPCL_DIR=<path/to/pcl/cmake/config/file> ..
make
```

## Run

```
build/odm_meshing -inputFile sample_data/merged.ply -outputFile sample_data/odm_mesh.ply -logFile sample_data/odm_meshing_log.txt -maxVertexCount 1000000 -octreeDepth 9 -samplesPerNode 1.0 -solverDivide 12 -verbose
```