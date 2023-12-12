Certainly! Here is the raw Markdown code:

```markdown
# Geospatial Intelligence Workshop

This repository contains code and data for a geospatial intelligence workshop covering unsupervised land cover classification with Sentinel-2 data.

## Setting up the Environment

### Prerequisites
Make sure you have the following installed on your local machine:

- Python 3.8 or higher
- Docker

### Running the Web Application

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Romanian-Space-Initiative/Geospatial-Intelligence-Workshop.git
   cd Geospatial-Intelligence-Workshop/webapp
   ```

2. **Build and run the Docker container:**

   ```bash
   docker-compose up --build
   ```

3. **Open your web browser and go to** [http://localhost:5001](http://localhost:5001) **to access the web application.**

## Running the Unsupervised Classification Workflow

For the first part of the workshop, we will use a Google Colab notebook. Follow these steps:

1. **Open a new notebook using your Google account:** [Google Colab](https://colab.research.google.com/).

2. **Download the following files locally:**

   - All .tif images from the "S2_data" folder
   - All files from the "ValidationData" folder
   - The notebook "Sentinel2_unsupervised_classification.ipynb"

3. **In Google Colab, click on** File -> Upload notebook **and upload the** "Sentinel2_unsupervised_classification.ipynb" **notebook.**

4. **In the Files tab on the left, create a new folder named** "S2_data." **Upload the .tif images to this folder using the three dots menu.**

5. **Upload each file from the** "ValidationData" **folder separately.**

   **Note:** Allow all files to fully upload before proceeding.

6. **Run the cells in the notebook to perform the unsupervised land cover classification with Sentinel-2 data.**

## Directory Structure

- `webapp/`: Contains the Flask web application code.
- `satellite_data/`: Contains Jupyter notebook for unsupervised land cover classification with Sentinel-2 data.
- `validation_data/`: Contains files for validation data points.

Feel free to reach out if you have any issues or questions!
```