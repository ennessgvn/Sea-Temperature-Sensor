# Sea Temperature Sensor 


First, let's talk about what a temperature sensor is. They are sensors that measure the ambient temperature precisely, convert the analog data obtained into digital value and turn it into a voltage output. There are times when many people want to swim in the seas with pleasure. However, he has doubts that the temperature value of the sea will not be suitable for this. It is a known fact by studies that the temperature of the sea for swimming should be between 22-29 degrees. With this sensor, which is planned to be used in beaches and outdoor pools, it will be possible to observe whether the temperature of the water is suitable for swimming.

![alt text](https://staticb.yolcu360.com/blog/wp-content/uploads/2019/06/14190957/Demre-Sahili--e1560528628721.jpeg)

# Working Principle of Temperature Sensor
The sensor, which takes the instantaneous temperature value as an input, first examines this analog value through a microcontroller. This analog value is divided into 10-bit values and 5000mV intervals in order to have high sensitivity. This allows the sensor to hold data with high precision. Each temperature value will have a voltage value assigned to it. In this way, the output voltage indirectly shows us the temperature. It can be shown to the people there on the LCD screens placed in certain parts of the beaches. So people can understand whether the temperature is suitable for swimming.

![alt text](https://cdn.pixabay.com/photo/2021/03/26/13/42/summer-6125976_960_720.png)


## 1) Used Components
1)Arduino Uno
2)LM35 Temperature Sensor
3)330 Ohm Res

## 2) LM35 Temperature Sensor
LM35 is a temperature measuring device having an analog output voltage proportional to the temperature. It provides output voltage in Centigrade (Celsius). It does not require any external calibration circuitry. The sensitivity of LM35 is 10 mV/degree Celsius.


### Datasheet

![LM35 Datasheet](https://user-images.githubusercontent.com/79998692/172068074-da3f04ca-345d-4d62-865e-709cf038cee1.PNG)


### Circuit on Board
![WhatsApp Image 2022-06-05 at 22 55 17](https://user-images.githubusercontent.com/79998692/172068276-470e92f7-0493-4ffc-ac8b-7dd1df579be9.jpeg)



### Code of Arduino

![Arduino Kodu](https://user-images.githubusercontent.com/79998692/172068427-077b7f05-560d-4585-a628-b863b8f51a76.PNG)


### Front Panel in Labview

![WhatsApp Image 2022-06-05 at 03 55 03 (1)](https://user-images.githubusercontent.com/79998692/172068455-e9a31587-acf0-470f-a8c5-33604b440ac5.jpeg)

![WhatsApp Image 2022-06-05 at 03 55 03 (2)](https://user-images.githubusercontent.com/79998692/172068457-a374f68a-52ac-4f85-a617-d3ec5e0730e2.jpeg)
