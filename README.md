# 📍 PlanIt

PlanIt is an iOS app built with **SwiftUI** and **MapKit** as part of UNC AppTeam’s bootcamp final project.  
It helps users **search, view details, and plan itineraries** using TripAdvisor’s Content API.  
The app has a **map interface** and **tabbed navigation** to create a simple trip‑planning experience.

<img width="275" height="500" alt="image" src="https://github.com/user-attachments/assets/0cbf74e3-3df1-4271-a237-ff074f8c9f1a" /> <img width="275" height="500" alt="image" src="https://github.com/user-attachments/assets/3e5088ba-c691-4c7c-8ee6-c97569a957d4" /> <img width="275" height="500" alt="image" src="https://github.com/user-attachments/assets/063be4f5-b45f-4bd9-8d01-ad66c9c5a957" />

## ✨ Features
- 🗺️ **Interactive Map**  
  Displays planner items as markers using MapKit

- 🔎 **Search Integration**  
  Uses TripAdvisor’s API to search for locations by query and category. Results can be added directly to the planner.

- 📑 **Details View**  
  Shows location details (name, address, rating, hours, description) and photos.  
  Includes a button to add the location to the planner with coordinates.

- 📱 **Tabbed Interface**  
  **Home** → Planner list with editable items.  
  **Search** → API‑powered search view.  


## Challenges and Future Additions 

### Challenges
- **API Key Restrictions** – Matching IP ranges didn’t always work and need to look into how I could expand API usage.
- **Async/Await in SwiftUI** – Managing state updates while fetching data was hard to manage.
- **TripAdvisor API Search** — The Search feature on TripAdvisor wasn’t the best, as it only checks keywords and doesn’t account for context, categories, or relevance beyond simple text matching.
- **Planner Integration** – Mapping API results into `plannerItem` with coordinates and optional fields was tricky.  
- **UI Consistency** – Balancing SwiftUI layouts (scroll views, bottom sheets, tab views) with clean design took iteration.   

### Future Additions
- **Custom Time Selection** – More ranges for times to be selected from.  
- **Expanded API Data** – Pull in reviews, nearby attractions, and restaurants for richer trip planning -> maybe switch to Google Maps API entirely.
- **Offline Mode** – Cache planner items and location details for use without internet.  
- **Enhanced Map Features** – Add draggable pins, route visualization, and clustering for multiple events.  
- **UI Polish** – Improve styling, animations, and accessibility for a smoother experience.  
- **Sharing & Export** – Allow exporting itineraries as text, PDF, or sharing with friends.  
