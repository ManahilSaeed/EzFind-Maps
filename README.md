# 📍 Ez-Find Maps – Interactive Map & Route Planner  

An interactive, responsive map application built as part of the University of Toronto’s **ECE297 Software Design & Communication** course.  
Due to **academic confidentiality**, the full source code cannot be published. This repository instead showcases the project’s design, features, and visual demos.  

---

## ✨ Features  

- 🔎 **Smart Search & Autocomplete** – quickly find intersections, addresses, and points of interest.  
- 🗺 **Pathfinding Algorithms** – efficient routing powered by **Dijkstra’s** and **A\*** algorithms.  
- 🎨 **Customizable Map Layers** – night mode + toggleable layers for POIs (cafes, restaurants, landmarks, etc).  
- 📧 **Email Directions Function** – send routes directly to your inbox for **offline access** (no need to rely on screenshots).  
- 🚇 **Transit Integration** – includes **TTC subway and streetcar lines** for multimodal navigation.  

---

## 📸 Key Features  

Here are some examples of the app in action:  

### 1. General View
*Main interactive map with POIs and navigation.*  

<p align="center">
  <img src="images/All POI.png" width="50%">
  <img src="images/Info Page.png" width="40%">
</p>


### 2. Light/Dark Mode Toggle
*Customizable night mode for easier viewing.*  
<p align="center">
  <img src="images/Light mode 3.png" alt="Map View" width="45%">
  <img src="images/Dark mode.png" alt="Night Mode" width="45%">
</p>


### 3. Customizable Points of Interest
<p align="center">
  <img src="images/Layer Toggle.png" alt="customized layers" width="51%">
  <img src="images/Customized POI.png" alt="filtered poi" width="40%">
</p>

### 4. Pre-Saved Maps
<p align="center">
  <img src="images/NYC Map Load.png" width="65%">
  <img src="images/Pre-saved Maps.png" width="22%">
</p>

### 4.Path-Finding and Directions
<p align="center">
  <img src="images/Pathway Finder Visualization.png" width="45%">
  <img src="images/Pathway Finder Directions.png" width="45%">
</p>

### 5.Email Directions
<p align="center">
  <img src="images/Email sent confirmation.png" width="55%">
  <img src="images/EmailSent.png" width="30%">
</p>



---

## 🔍 Focus  

- **Usability:** Designed for quick and intuitive navigation.  
- **Responsiveness:** Optimized for smooth performance even with large datasets.  
- **Reliability:** Features like the email directions function ensure stress-free use, even in low-connectivity areas (e.g., TTC subway).  

---

## 📌 Technologies Used  

- **C++ & GTK** for core map rendering and GUI.  
- **A\* / Dijkstra** for efficient routing.  
- **Multithreading** for performance optimization.  
- **libcurl (SMTP)** for email integration.  

---

## 📚 Acknowledgements  

Developed as part of **ECE297 – Software Design & Communication** at the University of Toronto.  
