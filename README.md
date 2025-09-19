# ositn-framwork
# OSINT Web Tool

This project aims to create a web-based OSINT tool with various search functionalities, designed to be integrated into a website. It will connect to user-provided CSV databases.

## Project Structure

```
osint_tool/
├── frontend/             # Contains HTML, CSS, JavaScript for the user interface
│   ├── index.html
│   ├── style.css
│   └── script.js
├── backend/              # Contains Flask application for API endpoints and database interaction
│   ├── app.py
│   └── requirements.txt
├── data/                 # Directory for user's CSV databases
│   ├── num_data.csv
│   ├── aadhar_data.csv
│   └── ...
└── README.md
```

## Technologies Used

*   **Frontend:** HTML, CSS, JavaScript (for animations and interactivity)
*   **Backend:** Python (Flask) for API development
*   **Database:** CSV files (user-provided)

## Core Functionalities (based on user's request)

*   `/num` — Find details from a 10-digit mobile number
*   `/aadhar` — Lookup info from a 12-digit Aadhaar
*   `/email` — Check breaches linked to an email
*   `/vehicle` — Get RC, owner & insurance details
*   `/pak` — Pakistan mobile number info
*   `/cnic` — Pakistan CNIC info
*   `/ration` — Ration card info lookup
*   `/leak` — Breach lookup by email
*   `/fastag` — FASTag info by RC number
*   `/vnum` — Vehicle number lookup
*   `/upi2num` — Fampay UPI ➡️ mobile number
*   `/upiinfo` — UPI ID information lookup
*   `/credits` — Check remaining balance & searches (Placeholder for now)

## Integration

The tool will be designed as a standalone web application that can be embedded into an existing website using an iframe or similar method. The size will be optimized for this purpose.

