# Find My Device UI Clone

A responsive **Find My Device** UI clone built with **Next.js**, **React**, and **Leaflet.js**, using dummy data. This project lets you view a list of devices, see their locations on a map, and check detailed information. You can also simulate actions like **ringing** or **factory resetting** a device.

---

## Features

- Display a list of devices with name and location.
- Show device locations on a **Leaflet map** with markers and popups.
- Device details panel showing latitude, longitude, and location.
- Simulate **Ring Device** and **Factory Reset** actions.
- Modern, visually appealing layout using **plain CSS** (cards, hover effects, shadows).

---

## Installation

1. **Clone the repository**

```bash
git clone <your-repo-url>
cd find-my-device-clone
```

2. **Install dependencies**

```bash
npm install
```

> Make sure you have **Node.js** and **npm** installed on your system.

---

## Running the Project

Start the development server:

```bash
npm run dev
```

Open your browser and go to:

```
http://localhost:3000
```

- The UI should load with **device list**, **map**, and **device details**.
- Clicking a device in the list will highlight it and show its details.
- Use the buttons to **simulate actions**.

---

## Project Structure

```
find-my-device-clone/
├── app/                  # Next.js App Router pages
│   └── page.js           # Main page with layout (device list, map, details)
├── components/           # Reusable React components
│   ├── DeviceList.jsx    # Lists all devices
│   ├── DeviceItem.jsx    # Individual device card
│   ├── DeviceDetails.jsx # Selected device details with actions
│   └── MapView.jsx       # Leaflet map showing device markers
├── styles/               # Global CSS
│   └── globals.css       # Layout and styling for cards, map, header
├── utils/                # Utility files
│   └── dummyData.js      # Dummy JSON data for devices
├── package.json          # Node.js dependencies & scripts
└── README.md             # This file
```

---

## Dependencies

- **Next.js** – React framework for building modern web apps.
- **React** – Component-based UI library.
- **Leaflet.js** – Interactive maps library.
- **react-leaflet** – React wrapper for Leaflet.

---

## Notes

- **Dummy data** is used; no backend or database is connected.
- **Map markers** are fixed and generated from dummy latitude/longitude.
- UI is built using **plain CSS** for simplicity and compatibility.

