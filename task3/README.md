# weather_ext2

A JupyterLab extension to get weather data for cities. The data is imported into the kernel as variables in the user's namespace.

## Requirements

* JupyterLab >= 2.0

## Install

Make sure you have Conda installed in your system.

Create a Conda environment with the following command

```bash
conda create -n jupyterlab-ext --override-channels --strict-channel-priority -c conda-forge -c jupyterlab cookiecutter nodejs
conda activate jupyterlab-ext
```

```bash
cd WeatherJupyterLab
./install.sh
jupyter labextension install weather_ext2
```