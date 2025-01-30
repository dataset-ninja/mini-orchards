Dataset **Mini-Orchards** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4ODBfTWluaS1PcmNoYXJkcy9taW5pLW9yY2hhcmRzLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogImxQRmhDOUJOTWd2OXlVblJiL3pqQjYyQTh3NTEwRkE0c3E1Nk5jaUZlWm89In0=)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Mini-Orchards', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/dylanhasperhoven/mini-orchards).