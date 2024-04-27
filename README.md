# What is it?

A data pipeline that pulls data from NASA asteroids api and 
stores it to a postgresql database server using airflow, docker, postgresql, and python. I used dbt to model the data once the data is populated in the postgresql server.

# Data pipeline from NASA api to postgresql server 
<style>
  .image-container {
    display: flex;
    justify-content: space-between;
    width: 100%;
  }
  .image-container img {
    max-width: 50%;
    height: auto;
  }
</style>
![alt text](image.png) 
<div class="image-container">
    <img src="image-13.png" alt="alt text" width="400" height="400">
    <img src="image-2.png" alt="alt text" width="400" height="400">
</div>
# Dbt models

## Asteroids that orbit Earth model
![alt text](image-11.png) ![alt text](image-8.png)
## Asteroids population distribution animal size comparison model
![alt text](image-12.png) ![alt text](image-7.png)
## Hazardous vs non-hazardous asteroids
![alt text](image-10.png) ![alt text](image-9.png)