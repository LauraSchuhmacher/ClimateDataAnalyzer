# Climate Data Analyzer
## Introduction
Climate Data Analyzer is a tool designed to help you analyze and visualize climate data from the past years based on weather stations.

## Run it locally
### Prerequisites
Make sure you have the following installed:
- Git
- Python
- Docker

### Installation
#### 1. Clone Git Repository
```bash
$ git clone git@github.com:LauraSchuhmacher/ClimateDataAnalyzer.git
```
#### 2. Install Dependencies
```bash
$ pip install -r requirements.txt
```
#### 3. Docker
```bash
$ docker-compose up --build
```

## Running the App
1. Start Docker. 
2. Start the `climatedataanalyzer` container.
3. Open your browser and navigate to [http://localhost:5000](http://localhost:5000).

## Run the container

### Prerequisites - Container

- Docker

Or

- Windows Subsystem for Linux (WSL)
- Podman

### How to - Container

To pull and run the container, run:

```bash
docker run -p 5000:5000 ghcr.io/lauraschuhmacher/climate-data-analyzer:latest
```

or

```bash
podman run -p 5000:5000 ghcr.io/lauraschuhmacher/climate-data-analyzer:latest
```

## Rules
#### Frontend
* Functions are declared in camelCase
* Variables are declared in camelCase

#### Backend
* Functions are declared in snake_case
* Variables are declared in snake_case

