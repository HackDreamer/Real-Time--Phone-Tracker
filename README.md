# Real-Time--Phone-Tracker
📍 Phone Number Location Tracker
This project is a Python-based tool that allows you to trace the approximate location of a phone number using public APIs and libraries. It utilizes phonenumbers, geocoder, folium, and the OpenCage Geocoding API to fetch and visualize the phone number’s general location on a map.

🚀 Features
  - Extracts country, region, and service provider from a phone number.
  - Retrieves geographical coordinates using OpenCage API.
  - Displays the location on an interactive map with folium.
  - Simple and beginner-friendly Python implementation.
  
🛠 Requirements
   Install the required Python packages:
   
    pip install phonenumbers
    pip install folium
    pip install geocoder
    pip install opencage

You also need to create an account at OpenCage Geocoder to obtain a free API key.

🔐 OpenCage API Key

   To use OpenCage:
   
    - Sign up at opencagedata.com
    - Get your API key
    - Replace "YOUR_OPENCAGE_API_KEY" in the script with your key
    
   key = "YOUR_OPENCAGE_API_KEY"
   geocoder_api = OpenCageGeocode(key)

💻 Usage
  1. Run the Script:
      pythontracker.py
  2. Input the phone number in international format(eg,.+441632960961).
  3. The script will:
      - Phares and extraction location details.
      - Use Opencage to get latituted and longitude.
      - Gendrate an HTML map with a marker for the location.
      - 
📤 Sample Output

     Location: California
     Carrier: Verizon Wireless
     Latitude: 36.7783
     Longitude: -119.4179
 
⚠️ Disclaimer

This tool provides an approximate geographic location based on the phone number's country code, region, and carrier information. It does not track real-time locations or provide precise GPS coordinates. The location is derived from publicly available telecom metadata and geocoding services, and may not always reflect the phone number’s exact physical location. This tool is intended for educational and informational purposes only. It should not be used for any illegal, unethical, or privacy-invading activities. Always respect privacy and adhere to applicable laws when using such tools.


