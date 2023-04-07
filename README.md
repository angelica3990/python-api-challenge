## Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.

#### Part 1: WeatherPy
In this deliverable, you'll create a Python script to visualize the weather of over 500 cities of varying distances from the equator. 

You'll use the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and your problem-solving skills to create a representative model of weather across cities.

For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. 

To get started, the code required to generate random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:
- Latitude vs. Temperature
![image](https://user-images.githubusercontent.com/62813833/230535709-7764fa59-10b8-4268-b79b-04692304ddc0.png)
- Latitude vs. Humidity
![image](https://user-images.githubusercontent.com/62813833/230535720-a44da9f5-378b-467a-9c31-bc0d3e2aa7e6.png)
- Latitude vs. Cloudiness
![image](https://user-images.githubusercontent.com/62813833/230535735-d6a9493e-e501-4746-b438-b382c281e77a.png)
- Latitude vs. Wind Speed
![image](https://user-images.githubusercontent.com/62813833/230535748-39950be7-3308-454d-b818-a99d65bdf303.png)

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. 

Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values.
You should create the following plots:
- Northern Hemisphere: Temperature vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230535793-4f212b99-9180-4125-a522-786e5ded414d.png)
- Southern Hemisphere: Temperature vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230535814-c6d0a577-bc44-48de-b261-d1a2aa55b0c2.png)

- Northern Hemisphere: Humidity vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230535850-8727acb5-64d4-471c-9b2a-e302f80f3d10.png)
- Southern Hemisphere: Humidity vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230535872-8610a355-40e5-414d-be9f-8243a5daf1a4.png)


- Northern Hemisphere: Cloudiness vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230535902-3904993f-9af2-4dea-9614-fbaa1a2c0629.png)
- Southern Hemisphere: Cloudiness vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230535943-0b04adea-cde7-4270-95da-41f1e0718938.png)

- Northern Hemisphere: Wind Speed vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230536241-cb200643-5b5c-4d20-8134-b669de3e352f.png)
- Southern Hemisphere: Wind Speed vs. Latitude
![image](https://user-images.githubusercontent.com/62813833/230536211-b26f4df9-cb11-4555-be75-c13593e18cae.png)


#### Part 2: VacationPy
In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.
Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.
To succeed on this deliverable of the assignment, open the VacationPy.ipynb starter code and complete the following steps:
Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.


![image](https://user-images.githubusercontent.com/62813833/230537589-3c511174-0105-4e8c-8ec1-3e8f19be6011.png)


