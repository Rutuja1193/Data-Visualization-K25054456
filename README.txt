Olympic Performance Dashboard
7CCSMSDV — Introduction to Data Visualization
K25054456 | King's College London

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
LIVE WEBAPP (Recommended)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
A live hosted version is available at:
[INSERT GITHUB PAGES URL HERE]

Open the link in the latest version of Google Chrome.
No installation required.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
FILES IN THIS ZIP
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
index.html            — D3 webapp (main file)
olympic_medals.csv    — Olympic medals dataset (source data)
olympic_hosts.csv     — Olympic hosts dataset (source data)
README.txt            — This file

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
RUNNING LOCALLY (Fallback)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
The webapp loads CSV files using d3.csv() which requires
a local HTTP server. Do NOT open index.html by double-clicking
— it will not load the data.

Option 1 — Python (recommended):
  1. Open a terminal in this folder
  2. Run: py -m http.server 8000
  3. Open Chrome and go to: http://localhost:8000

Option 2 — WebStorm IDE:
  1. Open this folder as a project in WebStorm
  2. Right-click index.html
  3. Click "Open in Browser" — WebStorm serves it automatically

Option 3 — VS Code:
  1. Install the "Live Server" extension
  2. Right-click index.html
  3. Click "Open with Live Server"

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
BROWSER REQUIREMENT
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Google Chrome (latest version) is required.
Internet connection required to load D3 library from CDN.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
DATA SOURCES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
olympic_medals.csv and olympic_hosts.csv
Source: Olympics.com historical data
Available at: https://www.kaggle.com/datasets/piterfm/olympic-games-medals-19862018

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
LIBRARIES USED
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
D3.js v7.8.5
License: ISC
Source: https://cdnjs.cloudflare.com/ajax/libs/d3/7.8.5/d3.min.js
