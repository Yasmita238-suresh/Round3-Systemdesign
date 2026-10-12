
# Emergency Ambulance Dispatch Platform

## Round 3 – High-Level System Design

### Aim
To design a scalable Emergency Ambulance Dispatch Platform for handling emergency requests, ambulance allocation, and real-time location tracking.

### Features
- Dashboard to view emergency requests and ambulance availability.
- Request and cancel ambulance services.
- View ambulance details and emergency status.
- Simulated real-time ambulance tracking.
- Hospital information and availability.
- Seeded dummy data for ambulances, hospitals, and emergency requests.

### System Architecture
- **Frontend:** React and Tailwind CSS
- **API Communication:** REST API design
- **Database:** PostgreSQL for structured data
- **Caching:** Redis for frequently accessed data
- **Messaging:** Kafka or RabbitMQ for asynchronous communication
- **Scalability:** Load balancing and horizontal scaling

### Working
1. The user creates an emergency request.
2. The system identifies and assigns an available ambulance.
3. The user views ambulance details and simulated location.
4. The emergency status updates throughout the journey.
5. The request is completed on hospital arrival or cancelled when permitted.

### Note
This project is a frontend-only prototype using dummy data. Database, caching, messaging, and backend services are included as architectural design concepts and are not connected to live services.

### Result
The frontend prototype demonstrates the major features and high-level architecture of a scalable Emergency Ambulance Dispatch Platform.
