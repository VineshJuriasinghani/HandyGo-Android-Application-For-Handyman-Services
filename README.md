# OHandyGo-Android-Application-For-Handyman-Services

An Android application that connects buyers with nearby technicians (plumbers, electricians, carpenters, etc.) using Google Maps API for real-time location tracking.  
The app features dual authentication portals, distance-based technician filtering, request management, and a secure workflow for booking and completing services.  

---

## Key Features  
- Dual Authentication System – Separate login portals for buyers and technicians.  
- Technician Discovery – Buyers view nearby technicians on Google Maps with distance filtering.  
- Request Management – Buyers send service requests; technicians can accept or decline.  
- Fair Allocation – Once a request is accepted, the technician becomes unavailable for others until the task is completed or declined.  
- Privacy Protection – Contact details shared only after a request is accepted.  
- Work Status Tracking – Technician updates progress: *Start Work* → *Work Completed*.  
- Ratings & Reviews – Both buyers and technicians can rate each other after completion.  

---

## Tech Stack  
- Frontend: Java, XML, Material Design  
- Backend: PHP, Volley Library  
- Database & Hosting: MySQL (000webhost)  
- APIs: Google Maps API  

---

## Workflow  
1. Buyer Login: Selects category (plumber, electrician, etc.) and views nearby technicians on Google Maps.  
2. Request: Buyer sends a request; technician receives request with client distance visible.  
3. Acceptance: If technician accepts → contact details are exchanged; technician is locked to that request.  
4. Work Process: Technician updates status (working → completed).  
5. Feedback: After completion, both buyer and technician exchange ratings and reviews.  

---

## Future Enhancements  
- Real-time chat integration between buyers and technicians.  
- Online payment gateway for secure transactions.  
- Push notifications for request updates.  

   ```bash
   git clone https://github.com/yourusername/handyman-app.git
