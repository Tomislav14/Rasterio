# README.md

## Swiss DEM and Orthophoto Analysis

### DEM (Digital Elevation Model) Analysis

#### Key Details:
- **File:** 'swissalti3d_2021_2505-1138_0.5_2056_5728.tif'
- **Properties:**
  - **Data Type:** Float32
  - **Width x Height:** 2000 x 2000 pixels
  - **Coordinate Reference System (CRS):** EPSG:2056
  - **Pixel Resolution:** 0.5 x 0.5 units
  - **Min Elevation:** 427.84113
  - **Max Elevation:** 478.58655

#### Steps Performed:
1. Loaded the DEM file using Rasterio.
2. Read and stored the data into a NumPy array.
3. Displayed the DEM using Matplotlib with pixel size and title information.

### Orthophoto Analysis

#### Key Details:
- **File:** 'swissimage-dop10_2020_2505-1138_2_2056.tif'
- **Properties:**
  - **Data Type:** UInt8
  - **Width x Height:** 500 x 500 pixels
  - **Count (Bands):** 3
  - **CRS:** EPSG:2056
  - **Transformation:** Affine(2.0, 0.0, 2505000.0, 0.0, -2.0, 1139000.0)

#### Steps Performed:
1. Opened the orthophoto file using Rasterio.
2. Read and stored the data into a NumPy array.
3. Displayed the orthophoto using Rasterio's plotting functionality with title information.
