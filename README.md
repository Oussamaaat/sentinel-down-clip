# sentinel-down-clip 🛰️✂️

sentinel-down-clip is a Jupyter Notebook that simplifies the process of querying, downloading, and processing Sentinel satellite data. With its intuitive interface and comprehensive functionalities, it enables easy access to Sentinel data for various applications, including machine learning and deep learning.

## Key Features ✨

- 🌍 **Query and Download**: Query and download Sentinel data using the powerful "sentinelsat" Python library.
- 🌐 **Interactive ROI Selection**: Utilize the interactive Kepler.gl interface to select the Region of Interest (ROI) and visualize product footprints.
- 🗂️ **Organized Folder Structure**: Maintain an organized folder structure to manage and avoid clutter when downloading multiple products.
- ✂️ **ROI Clipping**: Clip downloaded raster data to your ROI, generating clean folders with usable TIFF files.
- 📚 **Bands Stacking**: Stack bands for further processing and analysis.
- 🛒 **Clustering**: Apply K-means clustering for unsupervised classification experiments.
- ⚙️ **Customizable and Extensible**: Modify and enhance the notebook to suit your specific requirements.

## Getting Started 🏁

1. Clone the repository: `git clone https://github.com/oussamaaat/sentinel-down-clip.git`
2. It is recommended to work in a venv named sdc_env.  
3. Install the required dependencies:  
   1. `pip install GDAL-3.2.3-cp38-cp38-win_amd64.whl`.
   2. `pip install sentinelsat keplergl numpy matplotlib scikit-learn`.
   3. If you face an error install the gdal wheel and keplergl seperately. 
4. Launch Jupyter Notebook: `jupyter notebook`
5. Open the "sdc_notebook.ipynb" notebook.
6. Run each cell sequentially, following the detailed instructions provided.

## Contribution and Feedback 🤝

Contributions, suggestions, and bug reports are highly appreciated! Feel free to open issues or submit pull requests in the repository. Your feedback and ideas will help improve the notebook and make it more valuable for the community.