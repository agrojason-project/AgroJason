![Image](images/logo.png)

##Description

AgroJason Project, is an automated hydroponic greenhouse which maintains the conditions of humidity, pH, light and temperature. The desirable values are saved in a database. It has 4 separate units, in order to have parallel cultivation. These units are connected to a UI system, so that the system is easily controlled by a user.

##Control Unit

Each unit has its own control unit. It is implemented on Arduino mini board. It has its own sensors in order to get values of:
Humidity: DHT11
Substrate humidity: Soil Humidity Hygrometer Moisture Detection Sensor
Light: Photoresistor
Temperature :DHT11 (it gets values of temperature and humidity)
PH :Liquid PH Sensor

So, as we get the condition values, we try to maintain them in the correct sum. In order to achieve this we have installed some mechanisms. Those are:

* A heat radiator system, using a resistor.
* A wet side system.
* Windows.
* A curtain
* A UV light.
* A water container

So let's describe how does it work:

* If the temperature is low, activate the radiator system.
* If the temperature is high, activate the wet side system.
* If the humidity is low, water the plant, using the water container.
* If the humidity is high, open the windows.
* If light is low, turn on the UV light.
* If light is high, close the curtains.
* For pH, we are not ready in this version to force it.

##Data Base

In the dataBase, we have the values of:

* Strawberry
* Bean
* Pepper
* Melon
* Tomato
* Eggplant
* Lettuce
* Watermelon
* Gerbera
* Gypsophile
* Clove
* Cucumber
