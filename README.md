🏢 Property Portfolio Mapper
A 100% web-based, privacy-focused tool to visualize real estate or insurance portfolios. This app allows you to upload an Excel file of property addresses and instantly plot them on an interactive map with Total Insured Value (TIV) and other custom data.

🚀 Features
Excel Support: Directly upload .xlsx or .xls files.

Automatic Geocoding: Converts text addresses to map coordinates using OpenStreetMap (Nominatim).

Dynamic Popups: Automatically displays all columns from your Excel (TIV, Policy #, Square Footage, etc.) when a pin is clicked.

Privacy First: All processing happens in your browser. Your data is never uploaded to a private server.

Completely Free: No API keys, no subscriptions, and no usage fees.

📋 How to Prepare Your Excel File
To ensure the map works perfectly, your Excel sheet should follow these simple rules:

Column Headers: The first row must contain headers.

Address Column: You must have a column named Address (or "Location"). This should contain the full address (e.g., 123 Main St, New York, NY).

Data Columns: You can include any other columns like TIV, Owner, or Notes. These will automatically appear in the popups.

🛠️ How to Use
Open the live link (hosted via GitHub Pages).

Click the "Choose File" button.

Select your Excel portfolio.

Wait for processing: To comply with free usage limits, the app processes one address per second. A progress bar will track the status.

Explore: Zoom in, pan around, and click on pins to see the specific details for each location.

🏗️ Technical Stack
Map Engine: Leaflet.js

Map Data: OpenStreetMap

Excel Parser: SheetJS

Geocoding: Nominatim

⚖️ Limitations & License
Speed: This app uses the free Nominatim API, which limits requests to 1 per second. Large portfolios (100+ properties) will take a few minutes to load.

License: This project is open-source and free to use for personal or commercial purposes.
