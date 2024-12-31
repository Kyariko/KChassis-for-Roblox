# K-Chassis
Kchassis is a basic raycast chassis implementation for Roblox games.
## 🔰 Download 
Head to [releases](https://github.com/Kyariko/KChassis-for-Roblox/releases) to get your package.
## 🔨 Setup

For a first try, i suggest a empty baseplate to get the basics.  
![1](https://github.com/user-attachments/assets/0d93294a-0581-4830-82c9-dd1a9d41798c)
#
To start, you gonna import from file, the package you just downloaded (rbxm file).  
![2](https://github.com/user-attachments/assets/883fe20c-e41c-445d-8c30-db39a9c49a31)
#
Now in Explorer, your Baseplate structure should look like this, adding "KyarModules", "Wheels" and "KChassis".   
![3](https://github.com/user-attachments/assets/eba1b124-78d7-4c93-bcd7-6dda6b12cec5)
#
After adding theses 3 assets, now place "KyarModules" in Replicated Storage, "Wheels" in ServerStorage and leave "KChassis" in workspace.  
![4](https://github.com/user-attachments/assets/2129944b-d84b-4280-ab10-19cbc291b159)
#
You will need now, a car model, if you don't have any, i'm giving you for free my car model in the [Github Repo](https://github.com/Kyariko/KChassis-for-Roblox/tree/main).  
![5](https://github.com/user-attachments/assets/e918965b-6898-4282-a3e6-584a247ba377)
#
So far you have this structure with Kchassis and your car model (Here it's called Sprinter) in workspace.  
![6](https://github.com/user-attachments/assets/316dc356-eaa4-484b-9b44-b5a2e66ad69c)
#
So now let's begin the real configuration of the car, first you need to open "KChassis" and unfold the "CarModelExample" Model.  
![7](https://github.com/user-attachments/assets/1a82000d-8308-453b-bafe-1736ff7387e7)
#
After that, in "KChassis", you will copy "Engine" Position from "CarModelExample" Model, and paste the position value to your car model, so you car model aligns with "Kchassis".  
![8](https://github.com/user-attachments/assets/c344baaf-06da-4a84-9e0b-d62991658aa4)
#
Next, you will move all parts from your car model, into "CarModelExample" Model.  
![9](https://github.com/user-attachments/assets/05eb564a-9cf1-4864-91b7-bbe151421903)
#
It should now look like this.  
![10](https://github.com/user-attachments/assets/bb677e39-81d8-40d9-be39-4c50fdfd3f73)
#
Then you will take all steering wheel related parts of your car model, and move them into "SteeringWheel" model.  
![11](https://github.com/user-attachments/assets/d6e4fc23-54bc-4768-866e-539ebdb4e333)
#
Now, in case if you have this configuration, the red parts should be on the right of the car, so here it's inversed, let's fix that.  
![12](https://github.com/user-attachments/assets/6d5dbd2a-d0c5-481d-b0f8-a3760e3ec008)
#
To fix this issue, you just select all parts of your car model (not the chassis), and do a 180 degrees rotation.  
![13_1](https://github.com/user-attachments/assets/285e89e1-687b-4dd5-9823-aea051134d40)
#
Now you can turn "Engine" part in "CarModelExample" Model transparency to 1, to have a better view.  
![14](https://github.com/user-attachments/assets/a4ca1b7c-30a1-4e0d-aadf-b102647efbe7)
#
Now move "Seat" in "CarModelExample" where you want your character to sit, be carefull, most of the time it should be way lower than the car seat.  
![15](https://github.com/user-attachments/assets/1ff3d91f-ab1e-45d0-8a42-e496f8a824bb)
#
You do the same for the steering Wheel parts called "MainSteer" and "Steer", and you align them at the same time to the car steering wheel.  
![16](https://github.com/user-attachments/assets/41bee0c5-cc35-4905-b394-13bfecc8946e)
#
After this, you will ajust the front Wheels on both side at the same time (just Horizontaly for now), to keep everything symetrical.  
![17](https://github.com/user-attachments/assets/67cddfae-aa51-4936-9c42-5adad06f7f55)
#
Then you do the same for the rear wheels (still only Horizontaly for now).  
![18](https://github.com/user-attachments/assets/9eb62cc0-313d-4d9b-81e9-c2d54a1aeafc)
#
Now you can finally ajust verticaly the 4 wheels at the same time (or front and back separately but Right side and Left side should be symetrical).  
![19](https://github.com/user-attachments/assets/5c0b01fc-b41b-4905-b35a-20e433be1759)
#
To finish this, select "MainSteer", "Steer", the 4 wheels (FR,FL,RR,RL), "Engine" and "Seat", and set the transparency to 1 for theses parts  
![20_1](https://github.com/user-attachments/assets/c0c96cee-3944-4133-a06f-a5080dd4f96c)
#
Et voila ! You finished the setup to get a working car, but it may look weird like here, wrong wheel sizes and more details to fix.  
For all of theses you suggest you to go to this part to see how to [customize](https://github.com/Kyariko/KChassis-for-Roblox/tree/main#%EF%B8%8F-customization) the config of your car to fix all details.  
![20](https://github.com/user-attachments/assets/1365c70a-9d21-49e9-930e-5b4f163a42ec)
## 🛠️ Customization

## License & Copyright

## 📜 License  
This project is licensed under the MIT License.  

Copyright (c) 2024 Kyariko.  
See the [licence](LICENSE) file for details.  
