### <img height="30" src="https://irrigation-monitor-app.herokuapp.com/static/images/icon.png" alt=""/> About the project:
It is the IoT Based `Smart Agriculture & Automatic Irrigation System` with `Nodemcu ESP8266`. Agriculture plays a vital role in the development of agricultural countries. Some issues concerning agriculture have been always hindering the development of the country. Consequently, the only solution to this problem is smart agriculture by modernizing the current traditional methods of agriculture.

Hence the method is making agriculture smart using automation and IoT technologies. Internet of Things (IoT) enables various applications of crop growth monitoring and selection, automatic irrigation decision support, etc. We proposed ESP8266 IoT Automatic irrigation system to modernize and improve the productivity of the crop.

A basic django based application which contacts with nodemcu collects the temperature, moisture and humidity data and plots the graph of it.
User has to register then login and give the id of the device in the website so that they can communicate with each other. <br>
The code for `nodemcu` is also given in this repo under the `IrrigationDevice` folder. <br>
You can give a unique id to your device and pass the same in website.

Setting up the django project :

1. Creating virtual environment:
```bash
python -m venv venv
```
2. Activate virtual environment

Linux:
```bash
source venv/bin/activate
```
Windows:
```cmd
./venv/Scripts/activate
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
4. Apply migrations: 
```bash
python manage.py migrate
```
5. Collect static files : 
```bash
python manage.py collectstatic
```
6. Start the development server: 
```bash
python manage.py runserver
```


