# Awesome Remote Sensing

Remote Sensing is a very exciting field full of potential. This is a curated list of awesome **open-source** and openly accessible remote sensing resources, tools, and datasets.

_Last updated: 2026-01_18_

## Table of Contents

- [Introduction & Portals](#introduction--portals)
- [Cloud-Native Geospatial](#cloud-native-geospatial)
- [Tools & Libraries](#tools--libraries)
  - [High-performance & Rust](#high-performance--rust)
- [Deep Learning & Computer Vision](#deep-learning--computer-vision)
  - [Foundation Models & Vision-Language](#foundation-models--vision-language)
- [Data Sources](#data-sources)
- [Courses & Learning](#courses--learning)
- [Research, Books & Awesome Lists](#research-books--awesome-lists)

---

## Introduction & Portals

- [NASA Worldview](https://worldview.earthdata.nasa.gov/) – Interactive browsing of global, full-resolution satellite imagery. [web:9]
- [Sentinel Hub EO Browser](https://apps.sentinel-hub.com/eo-browser/) – Easy-to-use interface for Sentinel, Landsat, and MODIS (free tier for many EO use cases). [web:9]
- [Google Earth Engine](https://earthengine.google.com/) – Multi-petabyte catalog of satellite imagery and geospatial datasets with planetary-scale analysis capabilities (free for research and non-commercial use). [web:9]
- [Earth as Art](https://www.usgs.gov/media/images/set/earth-art) – Curated artistic satellite imagery from USGS. [web:9]

---

## Cloud-Native Geospatial

The modern workflow focused on accessing data without downloading large files.

- [STAC (SpatioTemporal Asset Catalog)](https://stacspec.org/) – The standard for indexing and discovering geospatial assets. [web:9]
- [Cloud Optimized GeoTIFF (COG)](https://www.cogeo.org/) – An efficient format for hosted raster data. [web:9]
- [Microsoft Planetary Computer](https://planetarycomputer.microsoft.com/) – STAC-compliant catalog with a hosted JupyterLab environment for open datasets. [web:9]
- [stackstac](https://stackstac.readthedocs.io/) – Turn STAC collections into xarray data cubes. [web:9]
- [Semablu](https://console.semablu.com/py/stac) — STAC-compliant API for AI super-resolved 2.5m Sentinel-2 imagery (RGB+NIR), built on the Copernicus Sentinel-2 L2A archive.

---

## Tools & Libraries

- [QGIS](https://qgis.org/) – Leading open-source desktop GIS. [web:9]
- [leafmap](https://leafmap.org/) – Python package for interactive mapping and geospatial analysis. [web:9]
- [geemap](https://geemap.org/) – Interactive mapping with Google Earth Engine in Python. [web:9]
- [GDAL](https://gdal.org/) – The “Swiss army knife” for geospatial data translation. [web:9]
- [Orfeo Toolbox (OTB)](https://www.orfeo-toolbox.org/) – High-performance remote sensing image processing library. [web:9]
- [rioxarray](https://corteva.github.io/rioxarray/) – Geospatial xarray extension powered by rasterio. [web:9]
- [TorchGeo](https://github.com/microsoft/torchgeo) – PyTorch domain library providing datasets, samplers, and transforms for geospatial data. [web:13]
- [RSGISLib](https://www.rsgislib.org/) – Python library focused on raster remote sensing processing and analysis. [web:37]
- [xarray-spatial](https://github.com/makepath/xarray-spatial) – Fast raster-based spatial analytics built on xarray, Numba and Dask. [web:50][web:54]
- [cuSpatial / libcuspatial](https://github.com/rapidsai/cuspatial) – GPU-accelerated C++/CUDA library for vector geospatial operations in the RAPIDS ecosystem (open source). [web:48][web:56]

### High-performance & Rust

- [GeoRust](https://georust.org) – Ecosystem of geospatial tools and libraries written in Rust (geometry, projections, I/O, etc.). [web:46][web:51]
- [awesome-georust](https://github.com/pka/awesome-georust) – Curated list of geospatial software and libraries in Rust. [web:47]
- [gdal (Rust bindings)](https://github.com/georust/gdal) – Idiomatic Rust wrapper around GDAL for rasters, vectors and spatial references. [web:49][web:57]
- [gdal-sys](https://lib.rs/crates/gdal-sys) – Low-level GDAL FFI bindings for building custom high-performance Rust tools. [web:53]

---

## Deep Learning & Computer Vision

- [TorchGeo](https://github.com/microsoft/torchgeo) – Deep learning with geospatial data (datasets, samplers, transforms). [web:13]
- [segment-geospatial / samgeo](https://github.com/opengeos/segment-geospatial) – Tools to apply Segment Anything to geospatial data with good docs and examples. [web:26]
- [Clay Foundation Model](https://clay-foundation.github.io/model/) – Open-source foundation model for Earth, providing EO embeddings for downstream tasks. [web:21][web:27]
- [Solaris](https://github.com/CosmiQ/solaris) – Pipeline for deep learning on satellite imagery. [web:9]
- [DeepForest](https://github.com/weecology/DeepForest) – Python package for tree crown detection in airborne RGB imagery. [web:9]

### Foundation Models & Vision-Language

- [Awesome Remote Sensing Foundation Models](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models) – Curated list of RS foundation models and related work. [web:2]
- [Foundation Models for Remote Sensing and Earth Observation](https://github.com/xiaoaoran/awesome-RSFMs) – Survey repo with extensive model and p

