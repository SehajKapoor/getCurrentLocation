# Digital Farm
Digital Farm: A Data-Driven Approach to Precision Agriculture in Small Farms

# Farma App
The mobile application that we have created to calculate and provide irrigation requirements for a crop. The application obtains values of parameters like rainfall, humidity, luminosity etc. that affect irrigation requirements of a crop, using remote and on-ground sensors and then using suitable methods and knowledge, calculates the quantity of water required for irrigation daily. The backend algorithm calculates irrigation requirement and it is integrated with the front-end of the mobile app to be displayed to the farmers.
<hr/>



# Need
India is an agricultural country with a population of over 1.3 billion dependent on agriculture as their major source of food and over 82 million people estimated to be working directly/indirectly in the agriculture sector. The approximate land area under agriculture is 60.4% of the total land cover of the country. With this proportion of total people and total land available, and with challenges like resource scarcity, climate change etc. it becomes imperative that the requirements of any and all crops like the amount of water needed for irrigation, amount of nutrients to be supplied to the crop throughout its life cycle etc. be calculated precisely.
There are two steps to achieve this result, first is to collect the data/information that affects these requirements from the field continuously (i.e. it is an ongoing process) correctly. And, the second step is to use the data collected and apply our knowledge and correct methods to reach an error-free answer to the question of “How much water is needed for irrigation at each step of the crop cycle?” This is basically what our application achieves. Using remote sensors and IoT-based on-field sensors, relevant data is collected from the field and passed to our app and with our available knowledge and technology, we measure the crop’s irrigation need using this information, and then ultimately pass these values through an API to the app for it to be displayed on the screen for the application user.
<hr/>



# Working principle
On identifying the factors that determine the amount of water required for irrigation by any crop, in our case, paddy, we basically used IoT sensors on the ground and remote sensors to gather that data and applied the basic principle of the crop water needs to obtain the total amount of water needed for irrigation of the crop daily.
The basic principle used is that the irrigation water need of any crop is the difference between the amount of water that is lost through evaporation or transpiration and the amount of water that the soil receives. In other words, the difference between the total water need of the crop and the amount of rainfall which is available to the crop.
Irrigation requirement = Total water need – Effective rainfall available
The following factors affect the parameters in the above formula:
	Climate- Water need of crops mostly increases in a hot, windy, dry and sunny climate. More evaporation also happens in such climate.
	Humidity- With increasing humidity, the crop water need decreases.
	Sunlight- More the intensity of sunlight, more the water need of the crop.
	Temperature- With increasing temperature, the crop water need also increases.
	Wind speed- Higher the wind speed, higher the water need of the crop.
	Crop type- The type of crop decides the height of standing water needed or the saturation of soil necessary for the crop before planting. The period length of the crop season also determines the overall irrigation requirement of the crop.
	Growth stage of the crop- Depending on the phase of the crop cycle, the water need of the crop (dry harvested crops) varies. Mostly, a full grown crop with full coverage of the ground takes more water than a crop at say the seeding stage.
	Soil type- The kind of soil affects the amount of water that is stored near the root and the amount of water that is lost due to percolation.

We have designed prototype before actual implementation
https://app.uizard.io/p/c1541fe4
