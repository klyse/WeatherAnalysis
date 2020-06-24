# Weather analisis of Brunico

Playing around with Jupyter Notebook.

Jump to notebook file https://github.com/klyse/WeatherAnalysis/blob/master/Data/Analysis.ipynb

Source Data: http://wetter.provinz.bz.it/download-messdaten.asp

## Requirements

- Docker

## Getting started

Build the docker image run:
```
docker build -t weather .
```

Run the docker container run:
```
docker run --rm -it -v ${pwd}\data:/tf -p 8888:8888 weather
```

Open the suggested terminal link (`http://127.0.0.1:8888/?token=...`) to view the notebook.
