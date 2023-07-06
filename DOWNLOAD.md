Dataset **Aerial Sheep** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/E/8/mu/ue6RWTcjqkjij4RcGwanrW8UBWuuZGJkyAEGf6kgHGXhMaj0nrKcLNCQeody9jTnfKlHtGviaRgiAKY6ZBa5XueUDU1d0XIABT5s7iIji0QGdmxEHoRDJ4CJVFJu.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Aerial Sheep', dst_path='~/dtools/datasets/Aerial Sheep.tar')
```
The data in original format can be 🔗[downloaded here](https://universe.roboflow.com/riis/aerial-sheep/dataset/1/download)