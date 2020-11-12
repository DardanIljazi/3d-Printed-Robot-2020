# 3D Printed Robot

The goal is to make a little bluetooth robot commanded with a mobile application.

![3D printed robot, 3d rendering](Robot_2020_1.png)

## Result

### Robot

![3D printed Robot result](Result_1024x768.png)

### Mobile application

*WIP: The app should and will be modified or changed by any other app already in Play/App store, the code has to be changed accordingly in Arduino nano*



## Parts and prices

![3D printed robot, 3d rendering with titles for some parts](Robot_2020_1_explain.png)



## Price: less than 35$ (shipping costs included)

Components have been chosen with 2 main parameters:

- **Best vendor** rating (only vendors equal or above 98% of positive feedback have been chosen)
- **Lowest price** found, including shipping cost



|                           Product                            | Name                                                     | Quantity |    Price in $    |                                         Get Product | Comment                                                      |
| :----------------------------------------------------------: | -------------------------------------------------------- | :------: | :--------------: | --------------------------------------------------: | ------------------------------------------------------------ |
| [![L298n](L298N.png)](https://s.click.aliexpress.com/e/_AUgiWD) | L298N <br />Motors driver                                |    1     |       1.55       | [**Get**](https://s.click.aliexpress.com/e/_AUgiWD) |                                                              |
| [![Arduino Nano](Arduino_Nano.png)](https://s.click.aliexpress.com/e/_An73jR) | Arduino Nano<br />Microcontroller                        |    1     |       2.47       | [**Get**](https://s.click.aliexpress.com/e/_An73jR) |                                                              |
| [![18650 batteries holder](18650_batteries_holder.png)](https://s.click.aliexpress.com/e/_9RttAp) | 18650 battery holder                                     |    1     |        2         | [**Get**](https://s.click.aliexpress.com/e/_9RttAp) |                                                              |
| [![AT-09](at_09.png)](https://s.click.aliexpress.com/e/_A9LxwV) | AT-09<br />Bluetooth module                              |    1     |       1.63       | [**Get**](https://s.click.aliexpress.com/e/_A9LxwV) |                                                              |
|                                                              | Dupont wire <br />(*Female VS Female*, *10cm*, *10 pin*) |    1     |       0.54       | [**Get**](https://s.click.aliexpress.com/e/_98ks45) | Used to connect <br />AT-09 and L298N <br />with Arduino Nano pins |
|                                                              | Dupont wire <br />(*Male VS Male*, *10cm*, *10 pin*)     |    1     |       0.74       | [**Get**](https://s.click.aliexpress.com/e/_98ks45) | Used to connect motors<br />and battery pins with L298N      |
| [![GT2-6mm belt](GT2-6mm_belt.png)](https://s.click.aliexpress.com/e/_Acf6TL) | GT2-6mm belt                                             |    1     |       0.69       | [**Get**](https://s.click.aliexpress.com/e/_Acf6TL) |                                                              |
| [![M3 bolts](M3x12_bolts.png)](https://s.click.aliexpress.com/e/_9yCjq9) | M3x12 Bolts                                              |    1     |       2.08       | [**Get**](https://s.click.aliexpress.com/e/_9yCjq9) |                                                              |
| [![JGA25-370 motors](motors.png)](https://s.click.aliexpress.com/e/_AeoSBF) | JGA25-370 motors                                         |    2     |        7         | [**Get**](https://s.click.aliexpress.com/e/_AeoSBF) |                                                              |
| [![18650 Batteries](18650_batteries.png)](https://s.click.aliexpress.com/e/_9xaDaV) | 18650 LiitoKala 3500 mAh 3.7v<br />(*2pcs*)              |    2     |       5.97       | [**Get**](https://s.click.aliexpress.com/e/_9xaDaV) |                                                              |
| [![MR105ZZ bearing](MR105ZZ.png)](https://s.click.aliexpress.com/e/_AVCCDX) | MR105ZZ Bearings                                         |    1     |       3.10       | [**Get**](https://s.click.aliexpress.com/e/_AVCCDX) | Bearing to make the robot be flat on the floor, <br />this is **optional** <br />but is recommended so <br />robot doesn't lean on front or back |
|                                                              | **Total**                                                |  **13**  |    **27.77**     |                                                     | Equals to ~:<br />- 25.40 CHF<br />- 23.50 €                 |
|                                                              | Shipping cost                                            |          |        7         |                                                     | Shipping cost is **approximatively ~$7** <br />(to Switzerland), <br />since this depends in which country you are, it could differ. |
|                                                              | **<u>Total with shipping</u>**                           |          | **<u>34.77</u>** |                                                     | Equals to ~:<br />- 31.40 CHF<br />- 29.44 €                 |





# Documentation



## Printing 3D parts

Find parts to print in [Parts folder](Parts), they are already classified, print them with recommended printing settings below.

Default recommended printing settings are these:

- `Layer height`: `0.2 mm` 

- `Infill`: `50%`

- `Support`: `No`

- `Build plate adhesion`: `Brim`

- `Nozzle`: `0.4 mm`

  

| Picture of STL file                                          | Name                                                         |                   Other printing settings                    | Number of prints |
| ------------------------------------------------------------ | :----------------------------------------------------------- | :----------------------------------------------------------: | :--------------: |
| <br /><img src="01_Main_Bottom_Part.png" alt="01_Main_Bottom_Part" max-width="100%" /> | <br />[**01_Main_Bottom_Part.stl**](Parts/01_Main_Bottom_Part.stl) |                           <br />-                            |     <br />1      |
| <br /><img src="02_Pillar_For_Motor.png" alt="02_Pillar_For_Motor" max-width="100%" /><br /><img src="02_Pillar_For_Motor_Assembly.png" alt="02_Pillar_For_Motor_Assembly" max-width="100%" /> | <br />[**02_Pillar_For_Motor.stl**](Parts/02_Pillar_For_Motor.stl) |                           <br />-                            |     <br />2      |
| <br /><img src="03_Top_Part.png" alt="03_Top_Part" max-width="100%" /><br /><img src="03_Top_Part_Assembly.png" alt="03_Top_Part_Assembly" max-width="100%" /> | <br />[**03_Top_Part.stl**](Parts/03_Top_Part.stl)           |                           <br />-                            |     <br />1      |
| <br /><img src="04_Wheel_IN_Part.png" alt="04_Wheel_IN_Part" max-width="100%" /><br /><img src="04_Wheel_IN_Part_Assembly.png" alt="04_Wheel_IN_Part_Assembly" max-width="100%" /> | <br />[**04_Wheel_IN_Part.stl**](Parts/04_Wheel_IN_Part.stl) |                           <br />-                            |     <br />2      |
| <br /><img src="05_Wheel_OUT_Part.png" alt="05_Wheel_OUT_Part" max-width="100%" /><br /><img src="05_Wheel_OUT_Part_Assembly.png" alt="05_Wheel_OUT_Part_Assembly" max-width="100%" /> | <br />[**05_Wheel_OUT_Part.stl**](Parts/05_Wheel_OUT_Part.stl) | <br />`Layer height`: `0.05 mm` or if not possible: `0.1 mm` |     <br />2      |
| <br /><img src="06_L298N_bottom.png" alt="06_L298N_bottom" max-width="100%" /><br /><img src="06_L298N_bottom_Assembly.png" alt="06_L298N_bottom_Assembly" max-width="100%" /> | <br />[**06_L298N_bottom.stl**](Parts/06_L298N_bottom.stl)   |                           <br />-                            |     <br />1      |
| <br /><img src="07_Bearing_Maintainer_Under.png" alt="07_Bearing_Maintainer_Under" max-width="100%" /><br /><img src="07_Bearing_Maintainer_Under_Assembly.png" alt="07_Bearing_Maintainer_Under_Assembly" max-width="100%" /> | <br />[**07_Bearing_Maintainer_Under.stl**](Parts/07_Bearing_Maintainer_Under.stl) | <br />`Layer height`: `0.05 mm` or if not possible: `0.1 mm` |     <br />4      |



## After printing, before final assembly



