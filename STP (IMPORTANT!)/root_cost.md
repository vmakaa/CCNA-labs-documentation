<img width="1258" height="694" alt="image" src="https://github.com/user-attachments/assets/2056ac02-5883-472d-8445-8a6494ade9df" />


If root cost is the same, it will pick a neighboring switch with the lowest bridge priority to make the port connected to that switch a root port and then the port onm the 
lowest bridge ID switch neighbor a designated port

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/819dcc8f-6446-4416-bc32-8853e0cb184d" />


If you need to break the tie via root ID then, you llok at the neighboring switch's ports compared to your switch's ports and the neighboring port's port ID will be used to determine
your local switch's root port depending on if the neighbor's port is lower in port ID than your local port


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4b29841-156f-4827-9814-7c30273b5894" />
