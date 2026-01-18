
# High Sea - Yacht Voyage Planner ⛵

**High Sea** is a comprehensive web application designed for planning and booking luxury yacht voyages worldwide. The platform allows users to manage their profile, customize their maritime itineraries, choose premium yachts, and select additional attractions for a perfect sea vacation.

## 🌟 Key Features

* **User Authentication:** Complete Login and Registration system with data persistence.
* **Voyage Planning:** Users can select a primary destination, multiple stop-overs, and a specific departure date.
* **Yacht Fleet Selection:** A variety of luxury yachts (e.g., "Ivory", "Sapphire", "Almog") with different price points and amenities.
* **Activity Customization:** Add experiences like Dolphin Swimming, Scuba Diving, Full Board meals, or Spa treatments.
* **Event Styling:** Tailor the trip for specific occasions like Birthdays, Fishing trips, or Anniversaries.
* **Smart Shopping Cart:** Real-time summary of the planned trip before final confirmation.
* **Booking History:** Users can view their past orders and saved itineraries.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Flexbox layouts, Responsive design).
* **Logic:** Vanilla JavaScript (ES6+).
* **Data Management:** LocalStorage API for persisting user data and booking history.
* **UI/UX:** Dynamic Single Page Application (SPA) feel using DOM manipulation to switch between views.

## 📁 Project Structure

* `index.html`: The main structure of the application.
* `newIndex.css`: Custom styling, including unique background transitions and interactive button effects.
* `newIndex.js`: The core logic handling authentication, cart management, and rendering of orders.

## 🚀 Getting Started

1. **Clone the repository:**
```bash
git clone https://github.com/rutSimanTov/Yacht-Trip-Planner.git

```


2. **Open the project:**
Simply open the `index.html` file in any modern web browser.
3. **Usage:**
* Register a new account or use the default credentials (e.g., `r@gmail.com` / `1111`).
* Start planning your voyage through the interactive steps.
* View your confirmed trips in the "Previous Orders" section.



## 📝 Implementation Details

The project utilizes a custom-built state management system using `LocalStorage` to simulate a database environment. It features dynamic rendering functions that build the UI based on user selections and stored arrays.
