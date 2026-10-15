# AquaSentinantal
A smart system created to monitor and detect leaks in underground pipes.

It monitors realtime vibrational values of two points at a distance to determine leak in the middle part (underground). We used SW-420 vibration module to get the vibrational values and analysis it in real time to predict a leak accurately.

<img width="1280" height="960" alt="WhatsApp Image 2026-10-15 at 7 32 03 PM" src="https://github.com/user-attachments/assets/55dacacd-e7e6-431f-be57-e4f6b658fb9c" />
As you can see in the above image, I have build a loop of water flowing to simulate real life pipes flow. I have used two SW-420 vibration module to get the vibration at two points located at a little distance from the leak point. I have also used 12V DC water pump in a plastic container to hold water. The realtime values from the vibration module goes straight to my laptop through arduino uno into a webpage created in HTML and JavaScript which not only shows realtime integer values but also plots realtime line graph of both points.

<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/ce29566d-68c5-402f-9328-394e80329588" />
In the above image you can see the webpage and the GUI.

<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/c610518e-9aa9-4bb6-b5e6-2390d387bdd8" />
Whenever there is a leak which is indicated in my model by opening the value labelled as the leak point, it creates a pressure drop which creates a vibration though the outwards of the pipe, which is detected by the sensors as it creates a peak in the graph.
