## EX 01 : Implementing various effects in a material such as emiss roughness and metallic properties in Unreal Engine 

## Reg no: 212224220073


## AIM :
To Implement various effects in a material such as emissive, roughness an metallic properties in Unreal Engine. 
## PROCEDURE :
1. Create Material
Open Unreal Engine. Right-click in Content Browser → Click Material → Name it M_Effect.


3. Open Material Editor
Double-click the material to open it.


5. Set Base Color
Add a Constant3Vector node → Choose a color. Connect it to Base Color.


7. Add Emissive Color
Add a Constant3Vector (color) and a Scalar Parameter (intensity). Multiply them and connect to Emissive Color.


9. Set Roughness
Add a Scalar Parameter → Connect to Roughness. Use 0.0 for smooth, 1.0 for rough.


11. Set Metallic
Add a Scalar Parameter → Connect to Metallic. Use values between 0.0 (non-metal) to 1.0 (metal).


13. Apply and Save
Click Apply and Save. 8. Use the Material
Drag it onto any mesh in the scene.


## Output : 

![image](https://github.com/user-attachments/assets/7b92d67f-cf8a-44ed-89b2-22d0e83a8eef)
![image](https://github.com/user-attachments/assets/37857505-9a24-4e2e-ae22-bc4f3dfe51e3)
![image](https://github.com/user-attachments/assets/6c0f71b7-eb61-437e-a14c-5ce109863b89)
![image](https://github.com/user-attachments/assets/83816fae-5b06-425d-b279-3154a33a23b3)





