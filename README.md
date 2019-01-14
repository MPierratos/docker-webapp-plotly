# Building a Dash Web App with Docker

Generate a docker container which builds a webapp using Dash (a python API that is built on top of Plotly.js, React, and Flask).

This web app is based on a sample from the plotly website (https://plot.ly/python/time-series/).

Here are some other recipes: https://github.com/plotly/dash-recipes

## Getting Started

#### 1. Install Docker Hub

Here are instructions to install Docker on Windows: https://docs.docker.com/docker-for-windows/install/


#### 2. Clone Repo

`git clone https://github.com/MPierratos/docker-webapp-plotly.git`

#### 3. Build Container

Run this command to run the app. Go to http://localhost:8081 to view.

`docker-compose up`

If you make adjustments to your dockerfile, you can recreate the build with:

`docker-compose up --build`
