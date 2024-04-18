# End-to-End-Azure-ML-Deployment

### Tools Requirements

1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)
4. [Postman](https://www.postman.com)

Create a new environment 

''' 
conda create -p realestate python==3.11.5 -y
'''

## Dataset

The dataset used for this project contains the following variables:

RealEstate.csv dataset (414)

- `X2 house age`: Age of the house in years 
- `X3 distance to the nearest MRT station`: Distance from the house to the nearest Mass Rapid Transit (MRT) station, in meters. 
- `X4 number of convenience stores`: Number of convenience stores nearby 
- `X5 latitude`: Latitude of the location of the house
- `X6 longitude`: Longitude of the location of the house
- `Y house price of unit area`: Price of the house per unit area (price per square foot or square meter)(target)
