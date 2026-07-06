# Devon Rama Wikunanda

Undergraduate Geodetic Engineering student at Universitas Diponegoro, Semarang, Indonesia. I build remote-sensing and geospatial-ML pipelines for environmental monitoring SAR–optical change detection, InSAR deformation, and land-cover classification with an emphasis on validation rigour and honest scoping.

## Focus Areas

- SAR–optical fusion (Sentinel-1 + Sentinel-2) for change detection and land-cover mapping
- InSAR time-series for land subsidence and coastal deformation (LiCSBAS)
- Geospatial machine learning (XGBoost, LightGBM, Random Forest) with spatial cross-validation
- Google Earth Engine + Python pipelines (rasterio, geopandas, GDAL) and spatial databases (PostGIS)

## Featured Projects

### [EUDR Deforestation Screening PBDS, Papua](https://github.com/devonrama/eudr-deforestation-demo)

Sentinel-1 / Sentinel-2 fusion pipeline screening a ~38,800 ha Indonesian oil-palm concession for forest loss after the EU Deforestation Regulation cutoff (2020-12-31). The primary detector is unsupervised SAR change-point detection radar penetrates the near-permanent tropical cloud cover that blinds optical-only methods confirmed by Sentinel-2 optical drops. Detected loss is cross-validated against three independent satellite references (RADD, Hansen GFC, JRC TMF), reaching ~0.81–0.85 strict-pixel and ~0.87–0.90 patch-area precision. A supervised XGBoost model is included as a documented comparison, with its honest (non-)result reported as part of the contribution. Capability demonstration, not a legal-grade compliance product.

**Stack:** Google Earth Engine, Python, rasterio, XGBoost, Folium

### [Coastal Subsidence & Flood Vulnerability Semarang–Demak](https://github.com/devonrama/coastal-subsidence-semarang-demak)

Sentinel-1 SAR flood-frequency and LiCSBAS InSAR subsidence mapping for the Semarang–Demak coast (2020–2025), fused into a per-kelurahan coastal-flood vulnerability typology. Built for the IEEE GRSS REACT EO4SDG challenge. SDG 11.5 / 13.1.

**Stack:** Sentinel-1, LiCSBAS, ESA SNAP, Python, geopandas

### [Karawang Industrial Zone Mapping](https://github.com/devonrama/karawang-industrial-mapping)

End-to-end remote-sensing pipeline mapping industrial land cover in the Karawang corridor, West Java, via Sentinel-1 / Sentinel-2 fusion and XGBoost classification. Produces 1,063 industrial polygons with documented human-in-the-loop refinement and an explicit limitations section.

**Stack:** Python, rasterio, geopandas, XGBoost, ESA SNAP

### [UAV Photogrammetry Accuracy Study](https://github.com/devonrama/uav-photogrammetry-accuracy-study)

Drone-imagery photogrammetry with GCP-based geodetic validation orthophoto and DSM generation and accuracy assessment using OpenDroneMap / WebODM.

**Stack:** OpenDroneMap, WebODM, GCP survey, Python

### [Headless SfM Engine](https://github.com/devonrama/Headless-SfM-Engine)

Async REST orchestrator for resource-constrained binary tools, demonstrated with COLMAP for Structure-from-Motion reconstruction. Single-tenant FastAPI service with subprocess timeout, payload validation, and VRAM-bounded preprocessing.

**Stack:** Python, FastAPI, COLMAP

## Technical Background

| Domain                    | Tools and Methods                                                       |
| ------------------------- | ----------------------------------------------------------------------- |
| Remote sensing            | Sentinel-1/2, Landsat, ESA SNAP, LiCSBAS, Google Earth Engine           |
| Change detection / InSAR  | SAR backscatter time-series, change-point detection, InSAR deformation  |
| Geospatial ML             | XGBoost, LightGBM, Random Forest, scikit-learn, spatial cross-validation |
| Geospatial Python         | rasterio, geopandas, GDAL, shapely                                      |
| Databases                 | PostgreSQL, PostGIS                                                      |
| Backend                   | FastAPI, async subprocess orchestration                                 |
| Geodetic computation      | Map projections, least-squares adjustment, satellite geodesy            |

## Currently Learning

- Deep learning for semantic segmentation in remote sensing
- Operational SAR/InSAR monitoring workflows (LiCSBAS, time-series)
- Reproducible geospatial ML pipelines determinism, spatial CV, validation rigour

## Contact

- Email (academic): <devonrama@students.undip.ac.id>
- Email (personal): <devonrama.w@gmail.com>
- Location: Semarang, Indonesia
