# DestinE Data Lake Gallery

**Welcome to the Destination Earth Data Lake Notebook Gallery!** <br>
Explore our collection of interactive Jupyter Notebooks, designed to help you work with the wide range of services offered by the DestinE Data Lake. Each notebook provides hands-on examples and practical guidance that you can adapt for your own projects. <br>
Use the tag filters to quickly find notebooks relevant to your interests or workflow. Tags group notebooks by topic, data source, or functionality, making it easier to navigate the gallery and locate the examples most useful for your work.

---

### Filter Notebooks by Tags










{button}`Access Token </galleries_by_tag/tag-access-token.md>`
{button}`API-key </galleries_by_tag/tag-api-key.md>`
{button}`Authentication </galleries_by_tag/tag-authentication.md>`
{button}`AVHRR </galleries_by_tag/tag-avhrr.md>`
{button}`C3S </galleries_by_tag/tag-c3s.md>`
{button}`Cluster </galleries_by_tag/tag-cluster.md>`
{button}`Core API </galleries_by_tag/tag-core-api.md>`
{button}`CQL2 </galleries_by_tag/tag-cql2.md>`
{button}`CUDA </galleries_by_tag/tag-cuda.md>`
{button}`cuDF </galleries_by_tag/tag-cudf.md>`
{button}`cuML </galleries_by_tag/tag-cuml.md>`
{button}`Dask </galleries_by_tag/tag-dask.md>`
{button}`Deep Learning </galleries_by_tag/tag-deep-learning.md>`
{button}`DestineLab </galleries_by_tag/tag-destinelab.md>`
{button}`Digital Twin </galleries_by_tag/tag-digital-twin.md>`
{button}`earthkit </galleries_by_tag/tag-earthkit.md>`
{button}`ECMWF </galleries_by_tag/tag-ecmwf.md>`
{button}`EODAG </galleries_by_tag/tag-eodag.md>`
{button}`ERA5 </galleries_by_tag/tag-era5.md>`
{button}`GFM </galleries_by_tag/tag-gfm.md>`
{button}`GPU </galleries_by_tag/tag-gpu.md>`
{button}`HDA </galleries_by_tag/tag-hda.md>`
{button}`Hook </galleries_by_tag/tag-hook.md>`
{button}`HTTP requests </galleries_by_tag/tag-http-requests.md>`
{button}`LI </galleries_by_tag/tag-li.md>`
{button}`Lightning </galleries_by_tag/tag-lightning.md>`
{button}`Machine Learning </galleries_by_tag/tag-machine-learning.md>`
{button}`Metop </galleries_by_tag/tag-metop.md>`
{button}`MTG </galleries_by_tag/tag-mtg.md>`
{button}`OLCI </galleries_by_tag/tag-olci.md>`
{button}`pyaviso </galleries_by_tag/tag-pyaviso.md>`
{button}`PyTorch </galleries_by_tag/tag-pytorch.md>`
{button}`Queryables </galleries_by_tag/tag-queryables.md>`
{button}`RAPIDS </galleries_by_tag/tag-rapids.md>`
{button}`ROI </galleries_by_tag/tag-roi.md>`
{button}`satpy </galleries_by_tag/tag-satpy.md>`
{button}`scikit-learn </galleries_by_tag/tag-scikit-learn.md>`
{button}`Sentinel-2 </galleries_by_tag/tag-sentinel-2.md>`
{button}`Sentinel-3 </galleries_by_tag/tag-sentinel-3.md>`
{button}`SEVIRI </galleries_by_tag/tag-seviri.md>`
{button}`STAC </galleries_by_tag/tag-stac.md>`
{button}`STACK </galleries_by_tag/tag-stack.md>`
{button}`Storage </galleries_by_tag/tag-storage.md>`
{button}`TensorFlow </galleries_by_tag/tag-tensorflow.md>`
{button}`Time Series </galleries_by_tag/tag-time-series.md>`
{button}`Token </galleries_by_tag/tag-token.md>`
{button}`Workflow </galleries_by_tag/tag-workflow.md>`
{button}`XGBoost </galleries_by_tag/tag-xgboost.md>`

---

### Services Overview

The DestinE Data Lake provides three main services to help you discover, process, and manage data:

* **[Harmonised Data Access (HDA)](https://hda.data.destination-earth.eu/stac)** – Browse Jupyter Notebook examples and Python tools for the DEDL Harmonised Data Access.
* **[STACK service](https://s3.central.data.destination-earth.eu/swift/v1/dedl_datacube)** – Leverage Dask for scalable, near-data processing of large datasets.
* **[HOOK service](https://odp.data.destination-earth.eu/odata/v1/)** – Create, manage, and automate workflows using the HOOK orchestration service.

---

### Using Notebooks on the DestinE Platform

If you are working in the DestinE JupyterLab environment, set up your environment as follows:

```bash
# 1. Create a virtual environment
python -m venv /home/jovyan/my_env

# 2. Activate the environment
source /home/jovyan/my_env/bin/activate

# 3. Install required dependencies
pip install -r /home/jovyan/datalake-lab/requirements.txt

# 4. Register the environment as a Jupyter kernel
python -m ipykernel install --name my_env --user
```

After installation, choose `my_env` from the Jupyter kernel menu to start running notebooks.

---

## Want to Contribute?

Have a useful notebook to share? Check out our [Contributing Guide](contribute.md) to learn how to add it to the gallery.

---

## Learn More

* [DestinE Documentation](https://destine-data-lake-docs.data.destination-earth.eu/en/latest/index.html) – Full platform and service documentation.
* [DestinE Data Portfolio](https://hda.data.destination-earth.eu/ui/catalog) – Browse available datasets.
* [API Documentation (Swagger)](https://hda.data.destination-earth.eu/docs/) – Explore the API endpoints and capabilities.
