# Windows-Sentinel-SIEM-lab
At a high level, I uesd Microsoft Azure to create a resource group within my free trial subscription. The resource group consistied of a virtual net/subnet, VM, NSG/Cloud FireWall(left open),Log analytics workspace (log repo)(to send all logs to a Azure monitoring agent),and a Windows Sentinel instance connected to the workspace. Sentinel was used to upload a watchlist, with KQL filtering for login attempts and IP addresses, to fascilitate the plotting of data on a map.  
# Languages Used
PowerShell: Extract RDP failed logon logs from Windows Event Viewer
Python: Conversion of IP addresses from QQL filtered table to geolocation map
# Utilities Used
ipgeolocation.io: IP Address to Geolocation API
Windows Security Events via AMA
# World map of incoming attacks after 24 hours (built custom logs including geodata)
![Untitled_Artwork](https://github.com/user-attachments/assets/ec6f0451-8a3a-493e-809d-e11306746f22)
![IMG_2756](https://github.com/user-attachments/assets/f734c03f-917f-4bb1-a696-960f4d8a66e3)
![IMG_2759](https://github.com/user-attachments/assets/bd2325c4-9e3d-4857-ac39-e340d3121a82)
![IMG_2760](https://github.com/user-attachments/assets/63531218-ab59-4736-992a-a3174e29fec6)
![IMG_2758](https://github.com/user-attachments/assets/bcf27a66-3325-4148-b9e9-c5f8c6cf9f5f)
