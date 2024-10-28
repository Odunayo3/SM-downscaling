
# Enhancing Soil Moisture Estimation with Machine Learning and Geostatistical Downscaling approach

## Overview
This project focuses on enhancing soil moisture estimation across West Africa by using machine learning and geostatistical downscaling approaches. We utilize the LightGBM and a hybrid LightGBMRK model, which combines machine learning with kriging, to improve the accuracy of ESA CCI Soil Moisture (SM) data when compared to in-situ measurements. The models are evaluated based on their ability to capture soil moisture dynamics across various land cover types and climate zones, with a particular emphasis on areas with complex interactions between vegetation and soil moisture.

## Environment Setup

To set up the environment, you will need to install Python and create a virtual environment with the necessary dependencies. Follow the steps below:

1. **Clone the Repository**
    ```bash
    git clone <repository_url>
    cd <project_directory>
    ```

2. **Create a Virtual Environment**
    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. **Install Dependencies**
    All required dependencies are listed in `requirements.txt`. Install them with:
    ```bash
    pip install -r requirements.txt
    ```

4. **Download Data**
    - Ensure that you have downloaded the ESA CCI Soil Moisture (SM) data and the in-situ measurements for West Africa.
    - Place these data files in a `data/` directory within the project folder.

## Dependencies

The key dependencies for this project include:
- **LightGBM**: For machine learning model implementation.
- **geopandas**: For handling geospatial data.
- **scikit-learn**: For machine learning utilities.
- **numpy** and **pandas**: For data manipulation and analysis.
- **pykrige**: For geostatistical kriging.
- **matplotlib** and **seaborn**: For data visualization.
- **rasterio** and **xarray**: For handling raster and NetCDF data formats.

Refer to `requirements.txt` for the full list of dependencies and versions.

## Running the Code

Once the environment is set up, you can run the code.

