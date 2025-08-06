# 🧭 Sri Vasavi Campus Navigation System

An **interactive route finder** using **Streamlit**, **NetworkX**, and **Matplotlib** to help users navigate **Sri Vasavi Engineering College** by computing and visualizing the **shortest walking path** between campus locations using the A\* algorithm.

---

## Key Features

- 📍 Graph-based visualization of campus locations (buildings & landmarks)
- 🔴 Highlights the shortest path using the A\* algorithm
- 📊 Displays weighted edges with distances
- 🖱️ Sidebar UI for easy start and destination selection
- 🧠 Heuristic-based smart routing

---

## 🛠 Technologies Used

- **Python 3.x**
- **Streamlit** – Web interface
- **NetworkX** – Graph creation and pathfinding
- **Matplotlib** – Visual display of graphs

---

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ramyao8/campus_navigation_system.git
   cd campus_navigation_system
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the application

bash
Copy
Edit
streamlit run campus_nav_sys.py
🧭 How to Use
Launch the app with Streamlit.

Use the sidebar to:

Select your current location

Select your destination

Click on "Find Shortest Path"

View the shortest path highlighted in red on the campus map.

⚠️ If source and destination are the same, a warning will be shown.

📍 Included Locations
Some sample locations included in the graph:

Academic Buildings: CSE1, CSE2, ECE1, ECE2, MECH, EEE, AIML, Civil, Polytechnic

Hostels: BoysHostel, GirlsHostel

Facilities: Canteen, Pharmacy, BusArea, Administration, Placements, BSH

Others: SaraswatiHimataStatue, CAI, Sports, Basketball Court, Gate

🧠 Algorithm
Uses the A* (A-star) algorithm for shortest path.

Employs a custom Euclidean-based heuristic for faster and more accurate routing.

Edge weights are randomly assigned for demo purposes and can be customized for real distances.

📌 Future Improvements
🔍 Add autocomplete and search for locations

📏 Show estimated distance and time

📱 Make UI responsive for mobile devices

📍 Add GPS/live tracking features

🔄 Zoom and pan functionality for the map


**📄 License**
This project is licensed under the MIT License.
