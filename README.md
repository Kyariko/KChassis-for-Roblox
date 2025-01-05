# K-Chassis
Kchassis is a basic and free raycast chassis implementation for Roblox games, made by Kyariko  
![ezgif-7-2ad1702c3d_1](https://github.com/user-attachments/assets/e154403a-3ac1-4f00-bf3c-5f2fe59370ef)

## Sections
- ### [Setup](https://github.com/Kyariko/KChassis-for-Roblox#-setup)
- ### [Setup Wheels](https://github.com/Kyariko/KChassis-for-Roblox#-setup-wheels)
- ### [Customization](https://github.com/Kyariko/KChassis-for-Roblox#%EF%B8%8F-customization)
- ### [Extras](https://github.com/Kyariko/KChassis-for-Roblox#extras-)
- ### [Controls](https://github.com/Kyariko/KChassis-for-Roblox#controls-)
## 🔰 Download 
Head to [releases](https://github.com/Kyariko/KChassis-for-Roblox/releases) to get your package.
## 🔨 Setup

For a first try, i suggest a empty baseplate to get the basics.  
![1](https://github.com/user-attachments/assets/0d93294a-0581-4830-82c9-dd1a9d41798c)
#
### 1. To start, you gonna import from file, the package you just downloaded (rbxm file).  
![2](https://github.com/user-attachments/assets/883fe20c-e41c-445d-8c30-db39a9c49a31)
#
### 2. Now in Explorer, your Baseplate structure should look like this, adding "KyarModules", "Wheels" and "KChassis".   
![3](https://github.com/user-attachments/assets/eba1b124-78d7-4c93-bcd7-6dda6b12cec5)
#
### 3. After adding theses 3 assets, now place "KyarModules" in Replicated Storage, "Wheels" in ServerStorage and leave "KChassis" in workspace.  
![4](https://github.com/user-attachments/assets/2129944b-d84b-4280-ab10-19cbc291b159)
#
### 4. You will need now, a car model, if you don't have any, i'm giving you for free my car model in the [Github Repo](https://github.com/Kyariko/KChassis-for-Roblox/tree/main).  
![5](https://github.com/user-attachments/assets/e918965b-6898-4282-a3e6-584a247ba377)
#
### 5. So far you have this structure with Kchassis and your car model (Here it's called Sprinter) in workspace.  
![6](https://github.com/user-attachments/assets/316dc356-eaa4-484b-9b44-b5a2e66ad69c)
#
### 6. So now let's begin the real configuration of the car, first you need to open "KChassis" and unfold the "CarModelExample" Model.  
![7](https://github.com/user-attachments/assets/1a82000d-8308-453b-bafe-1736ff7387e7)
#
### 7. After that, in "KChassis", you will copy "Engine" Position from "CarModelExample" Model, and paste the position value to your car model, so you car model aligns with "Kchassis".  
![8](https://github.com/user-attachments/assets/c344baaf-06da-4a84-9e0b-d62991658aa4)
#
### 8. Next, you will move all parts from your car model, into "CarModelExample" Model.  
![9](https://github.com/user-attachments/assets/05eb564a-9cf1-4864-91b7-bbe151421903)
#
### 9. It should now look like this.  
![10](https://github.com/user-attachments/assets/bb677e39-81d8-40d9-be39-4c50fdfd3f73)
#
### 10. Then you will take all steering wheel related parts of your car model, and move them into "SteeringWheel" model.  
![11](https://github.com/user-attachments/assets/d6e4fc23-54bc-4768-866e-539ebdb4e333)
#
### 11. Now, in case if you have this configuration, the red parts should be on the right of the car, so here it's inversed, let's fix that.  
![12](https://github.com/user-attachments/assets/6d5dbd2a-d0c5-481d-b0f8-a3760e3ec008)
#
### 12. To fix this issue, you just select all parts of your car model (not the chassis), and do a 180 degrees rotation.  
![13_1](https://github.com/user-attachments/assets/285e89e1-687b-4dd5-9823-aea051134d40)
#
### 13. Now you can turn "Engine" part in "CarModelExample" Model transparency to 1, to have a better view.  
![14](https://github.com/user-attachments/assets/a4ca1b7c-30a1-4e0d-aadf-b102647efbe7)
#
### 14. Now move "Seat" in "CarModelExample" where you want your character to sit, be carefull, most of the time it should be way lower than the car seat.  
![15](https://github.com/user-attachments/assets/1ff3d91f-ab1e-45d0-8a42-e496f8a824bb)
#
### 15. You do the same for the steering Wheel parts called "MainSteer" and "Steer", and you align them at the same time to the car steering wheel.  
![16](https://github.com/user-attachments/assets/41bee0c5-cc35-4905-b394-13bfecc8946e)
#
### 16. After this, you will ajust the front Wheels on both side at the same time (just Horizontaly for now), to keep everything symetrical.  
![17](https://github.com/user-attachments/assets/67cddfae-aa51-4936-9c42-5adad06f7f55)
#
### 17. Then you do the same for the rear wheels (still only Horizontaly for now).  
![18](https://github.com/user-attachments/assets/9eb62cc0-313d-4d9b-81e9-c2d54a1aeafc)
#
### 18. Now you can finally ajust verticaly the 4 wheels at the same time (or front and back separately but Right side and Left side should be symetrical).  
![19](https://github.com/user-attachments/assets/5c0b01fc-b41b-4905-b35a-20e433be1759)
#
### 19. To finish this, select "MainSteer", "Steer", the 4 wheels (FR,FL,RR,RL), "Engine" and "Seat", and set the transparency to 1 for theses parts  
![20_1](https://github.com/user-attachments/assets/c0c96cee-3944-4133-a06f-a5080dd4f96c)
#
### 20. Et voila ! You finished the setup to get a working car, but it may look weird like here, wrong wheel sizes and more details to fix.  
For all of theses you suggest you to go to this part to see how to [customize](https://github.com/Kyariko/KChassis-for-Roblox/tree/main#%EF%B8%8F-customization) the config of your car to fix all details.  
![20](https://github.com/user-attachments/assets/1365c70a-9d21-49e9-930e-5b4f163a42ec)

## 🔨🛞 Setup Wheels

### 1. In thew package you downloaded, in "ServerStorage/Wheels" you have one Wheel model.  
![Wheel_0](https://github.com/user-attachments/assets/2ad1220f-f525-4d8c-a50b-eda89aaa178f)

## 2. The model should containt Theses parts, a "Rim" part, a "Tire" part and a "Main" part.  
![Wheel_1](https://github.com/user-attachments/assets/144003a1-9864-4818-93d8-c3ccc771ef5a)

## 3. Now you checked everything, place copy the model to "Workspace" to start rigging it.  
![Wheel_2](https://github.com/user-attachments/assets/0e0a93b0-d581-4a06-bd01-f276bb43435f)

## 4. Now get your wheel model, if you don't have any, again im giving you one i made for free.  
![Wheel_3](https://github.com/user-attachments/assets/affad85e-e2f5-432a-8c6e-2ecae45ca9df)

## 5. After that open "CopyThisModelToRigWheels" model, and move "Main" into your wheel model.  
![Wheel_4](https://github.com/user-attachments/assets/99fa694b-0baa-477e-8081-2bffc94ba231)

## 6. Then, make it the primary part of your model like this.  
![Wheel_5](https://github.com/user-attachments/assets/5e5490a4-c15f-47ef-b969-cd29bf247c0c)

## 7. Next, you remane the tire mesh of your wheel model to "Tire" and the rim part to "Rim".  
![Wheel_6](https://github.com/user-attachments/assets/3250726f-b409-4499-b1d0-e4d49749c066)

## 8. Once you're done, you just copy "Tire" position, and paste it into "Main" position.  
![Wheel_7](https://github.com/user-attachments/assets/ab03e42f-36c5-49f1-9a9a-01e5a5994615)

## 9. After that you open "Main" in the wheel model and change "ID" value.  
## WARNING ⚠️ Two wheels models can't have the same ID value, otherwise wheels rigging will break as it can't choose between 2 same values.  
![Wheel_8](https://github.com/user-attachments/assets/bbea23ab-79f3-483f-a48d-c019b1f30af2)

## 10. Now we will check orientation, so all you have to do is right click "Main", and the click on "Show Orientation Indicator".  
![Wheel_9](https://github.com/user-attachments/assets/0b533a6d-ed38-44cd-9c88-d6c5f77b42c5)

## 11. And then, when you look at the front face of your wheel model, the blue cursor (with the small F letter in it), should be pointing to the left, if not, just rotate the "Main" part to align it properly.  
![Wheel_10](https://github.com/user-attachments/assets/1b5f4c65-9937-485a-8d36-2f62ac8acaa4)

## 12. Finally, you can put the rigged Wheel model back to ServerStorage/Wheels  
![image](https://github.com/user-attachments/assets/afe6931c-e665-4f32-942b-f4c2ec9c03ca)

## 🛠️ Customization

### So, for now if you just finished the setup, then you should have this beautifull car waiting to be properly configurated.  
![1](https://github.com/user-attachments/assets/d1139f5c-d236-4ae6-8c96-f49b82c6a31f)

### 1. First let's go into the chassis then go to KChassis/CarScripts and then we gonna first open "CMain".  
![2](https://github.com/user-attachments/assets/c72f467c-d550-49cd-b0ab-abc6c286803a)

### 2. Then, once you open the script, it should look like this at the very top, it may be scary but don't worry we just changing few values to configure the car.
![3](https://github.com/user-attachments/assets/ad9489cb-4f44-40d3-8f14-db2c0725f75a)

### 3. This part is telling where the car is, for now it's in workspace, but if you put the car in a folder, like "Cars" for example, it would be something like:  
```local CarLocation = workspace.Cars```
![4](https://github.com/user-attachments/assets/0342620d-a0a2-4529-80c3-344ba65b17dc)

### 4. From now on, you just have to change values here (we will see the exceptions later).
![Capture d'écran 2024-12-31 025502](https://github.com/user-attachments/assets/b2b603b7-587e-4955-8906-0c4054542abd)

### 5. First part called "Main", is where you can:  

![5](https://github.com/user-attachments/assets/6bdf12c2-1dba-40d9-8451-2a1605a2a737)
- Power = change Power of the car  
- Gears = the amount of gears (needs to be above 1)  
- MaxSpeed = set the maximum speed of the car  
- Grip = the level of grip the car has while driving  
- Handling = How strong/fast/easily the car turns  
- ShiftingTime = How fast the car changes gears

### 5. Second part called "Wheels", is where you can:  
![6](https://github.com/user-attachments/assets/c3f1afd8-251b-4a2e-a97d-47eeba5de43b)

- RimID = Specify the Id of the wheel model located in servertorage/Wheels/"YourWheelModel"/Main/ID  
- F/R Height = Height of the car, F for front and R for Rear
- F/R Size = Size of the car wheels, F for front and R for Rear  
- F/R Thickness = Thickness of the car wheels, F for front and R for Rear (This one is purely cosmetic, it doesn't affect handling like the other wheel settings)  

### 6. Last part is only if you know what you're doing or at least know bit of the chassis you're working on, if unsure DON'T TOUCH IT PLEASE.  
![7](https://github.com/user-attachments/assets/c6c49bcd-c08a-40fd-ba23-394d68e444d1)

- Stiffness = How hard the suspension is, everything above 3 is quite hard and can be really problematic depending the FPS of the player
- Damping = How limited the suspension movement is, as it can be hard but move slowly and vice-versa, 2 is a bit slow but good for hard suspensions, the lower this value is, the slower the suspension will move, the higher, the more wobbly the suspension will be.
- GearTable = Do not touch this under any circumstances, unless you know what you're doing or want to break the entire powertrain of the chassis.

### 7. Once you understood everything here, here's my configuration for the car.

![image](https://github.com/user-attachments/assets/51887765-0dfb-4fb3-a462-e862ceb951d3)

### 8. It's nearly done, now you also need to copy the stats to the script here

![image](https://github.com/user-attachments/assets/28d3e0ab-fd1c-4a69-bcbb-20fe36f2d94b)

## You just have to do this each time you change a value in the config files, double check both files to be sure ⚠️

![Enregistrement 2024-12-31 034028](https://github.com/user-attachments/assets/b87c5d4d-c5f0-48df-9c89-f7958e8debe3)

## Extras 💥
### If you want to change the Engine sound, you can open the Kchassis model and go in "Engine" (KChassis/Engine/EngineSample), and in SoundId you can put a sound of your choice, it must be a revloop (prefereably at high rpm)
![image](https://github.com/user-attachments/assets/a23def91-2651-40fa-a0ef-cf99d06bfb24)

### If you have headlights or brakelights parts you want to animate, you can rename them to "Headlights" and "Brakelights", the chassis will automatically recognize them and setup them automaticaly, but for now it must be a single part name like this for both situations, or just one part will work.

![image](https://github.com/user-attachments/assets/b19285f7-efe3-4b4b-8198-077f6aa5f328)


## Controls 🎮

### So far the controls are:  
- V key to flip instantly the car up side down (must be stationary)
- Left shift key for handbrake
- H key for headlights (if there's any headlights parts)

#### No controller/Mobile support at this moment, will be added in future versions (It's planned).

##  ✉️ Contribution and Contact
If you want to contribute to this project or help me with updates, you can contact me at Kyariko@outlook.fr or via koma_shi on Discord.
