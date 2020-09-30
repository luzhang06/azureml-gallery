# Component gallery
In this directory, you will find a wide array of components that can be used in Azure Machine Learning, contibuted by Microsoft and open source community. 

## Contributing

Instructions on how to contribute with your own component.

## Components
A component is self-contained set of code that performs one step in the ML workflow (pipeline), such as data preprocessing, model training, model scoring and so on. A component is analogous to a function, in that it has a name, parameters, expects certain input and returns some value. Data scientists or developers can wrap their arbitrary code as Azure Machine Learning component by following the component specification. Find the tutorials [here](https://aka.ms/aml-component) to get started.

Notebooks are provided to perform a quick demonstration of different algorithms such as Simple Algorithm for Recommendation ([SAR](https://github.com/Microsoft/Product-Recommendations/blob/master/doc/sar.md)).

| GitHub | Notebook | Azure Machine Learning studio | Type | Description |
| --- | --- | --- | --- | --- |
|![](https://az712634.vo.msecnd.net/content/14b2744cf8d6418c87ffddc3f3127242/9502630827244d60a1214f250e3bbca7/ba9e9cfd25a74690aec5983cb7cbf9ad/7662044d475d416ab30dc12fe41692e5/image?5131359820425363)[Simple Algorithm for Recommendation (SAR)*](https://github.com/microsoft/recommenders/tree/master/examples/00_quick_start) | <img width=21px src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/1200px-Jupyter_logo.svg.png">[sar_azureml.ipynb](https://github.com/microsoft/recommenders/blob/master/examples/00_quick_start/sar_movieratings_with_azureml_designer.ipynb)<br> | <img src="https://ms-toolsai.gallerycdn.vsassets.io/extensions/ms-toolsai/vscode-ai/0.5.1/1556575437282/Microsoft.VisualStudio.Services.Icons.Default" width=20px> [Open in Designer](sar_movielens_with_azureml.ipynb) | Algorithm | An example of how to utilize and evaluate SAR using the [Azure Machine Learning service](https://docs.microsoft.com/azure/machine-learning/service/overview-what-is-azure-ml) (AzureML). It takes the content of the [sar quickstart notebook](sar_movielens.ipynb) and demonstrates how to use the power of the cloud to manage data, switch to powerful GPU machines, and monitor runs while training a model.
|![](https://az712634.vo.msecnd.net/content/14b2744cf8d6418c87ffddc3f3127242/9502630827244d60a1214f250e3bbca7/df36abc90cf742abb7ed0375788afd84/e9a8067dbd0c4335b9a830530d536184/image?9379528722646815)[Spectral Residual Anomaly Detection](https://github.com/microsoft/anomalydetector/tree/master/aml_module#spectral-residual-anomaly-detection-module)| N/A | N/A| Services | Anomaly detection aims to discover unexpected events or rare items in data. It is designed to be accurate, efficient and general, using Spectral Residual (SR) and Convolutional Neural Network (CNN).|

## Reference papers
- Ren, Hansheng et al. “Time-Series Anomaly Detection Service at Microsoft.” Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (2019): n. pag. Crossref. Web.


<a href="https://trackgit.com">
<img src="https://sfy.cx/u/oFs" alt="trackgit-views" />
</a> views