### Micro-Jupyter

Built upon the fairly small alpine linux container image. Includes minimal libs to run jupyter running python3.

You can also just do ```bash 
docker pull danishabdullah/micro-jupyter:latest```

In order to do one off session
```bash
docker run --rm -p 8888:8888 danishabdullah/micro-jupyter:latest jupyter notebook --port=8888 --no-browser --ip=0.0.0.0```

This image is designed to be very small. Yet it is about 284.4 MB. If you know a way to make it smaller, file an issue and make a pull request. :)

