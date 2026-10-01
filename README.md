The idea behind my first hardware project was to build a system that can detect whether it is morning, night, or somewhere in between, using a light sensor. It may sound simple, but the creativity I added is what makes it worthwhile. I connected a servo motor whose rotation is controlled by the light sensor's input. The motor sits on a sheet of paper marked with a 90-degree scale, so wherever the servo points, you can tell what part of the day it is.

How it works: The light sensor continuously measures the brightness of its surroundings and sends that reading to the microcontroller as an electrical signal. The microcontroller converts the signal into a number and maps it to an angle between 0° and 90°. In bright light, such as midday, the servo turns toward one end of the scale. As the light fades toward evening, it moves gradually across the scale, and in darkness it settles at the opposite end. A pointer attached to the servo then shows the current part of the day on the paper scale, with no screen or manual input needed.

<img width="621" height="228" alt="b5" src="https://github.com/user-attachments/assets/920b3ed6-4c1a-4bbd-b707-982017b3d89d" />
<img width="267" height="481" alt="b6" src="https://github.com/user-attachments/assets/7da0c649-1729-42bd-9ef4-c7ed9420e600" />
<img width="864" height="528" alt="b1" src="https://github.com/user-attachments/assets/15f57949-d9d5-4840-b576-60cbddf0ec3a" />
<img width="873" height="514" alt="b3" src="https://github.com/user-attachments/assets/6d7040e7-bf53-4317-b731-2323baf051fd" />
<img width="611" height="376" alt="b4" src="https://github.com/user-attachments/assets/9b32de40-55ae-4ec1-a858-bb0ccfb544b5" />
<img width="875" height="521" alt="b2" src="https://github.com/user-attachments/assets/ca455b4e-bb9d-4a72-bd20-b5825f5de700" />
