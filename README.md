# asdi-examples
Jupyter Notebook examples related to the datasets in the [Amazon Sustainability Data Initiative (ASDI)](https://sustainability.aboutamazon.com/environment/the-cloud/amazon-sustainability-data-initiative) program.

In particular, these notebooks demonstrate how to query and access data from a [Spatial Temporal Asset Catalog (STAC)] of the open datasets that have been cataloged.

The notebooks are designed to work with [AWS SageMaker Studio Lab](https://studiolab.sagemaker.aws/) which you can use for free[^1], but should also work with other Jupyter Notebook environments. For some datasets an AWS account for requester pays charges may be required. See *Advanced Usage* below for more details. 

[^1]: Free allocation is time limited.

*Advanced Usage*
As a reminder these notebooks are for demonstration purposes using an experimental API. For large amounts of data access and analysis we recommend that you use Sagemaker Studio or deploy JupyterHub to an EC2 instance. In both cases you can optimize data access and minimize costs by running your instances in the same region as the data you intend to access.


## Datasets

* Copernicus Digital Elevation Model (DEM) [Glo-30 (30m) AWS Open Data](https://registry.opendata.aws/copernicus-dem/) <a href="https://studiolab.sagemaker.aws/import/github/https://github.com/developmentseed/asdi-examples/blob/main/examples/cop-dem-glo-30-stac-access.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/8c5378ff3bf6f71a57442940234293bd63c7ed2418d64f74f2bda3dc6f2904ed/68747470733a2f2f73747564696f6c61622e736167656d616b65722e6177732f73747564696f6c61622e737667" alt="Open In SageMaker Studio Lab" data-canonical-src="https://studiolab.sagemaker.aws/studiolab.svg" style="max-width: 100%;"></a>

* Sentinel 1 GRD [Sentinel-1 GRD AWS Open Data](https://registry.opendata.aws/sentinel-1/) <a href="https://studiolab.sagemaker.aws/import/github/https://github.com/developmentseed/asdi-examples/blob/main/examples/sentinel-1-stac-example.ipynb" rel="nofollow"><img src="https://camo.githubusercontent.com/8c5378ff3bf6f71a57442940234293bd63c7ed2418d64f74f2bda3dc6f2904ed/68747470733a2f2f73747564696f6c61622e736167656d616b65722e6177732f73747564696f6c61622e737667" alt="Open In SageMaker Studio Lab" data-canonical-src="https://studiolab.sagemaker.aws/studiolab.svg" style="max-width: 100%;"></a>
