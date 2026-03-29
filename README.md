# FlightSearch
Full‑stack web application for searching low‑cost flight prices, built with **ReactJS** (frontend) and **.NET** (backend demonstrate:Full‑stack web application for searching low‑cost flight prices, built with **ReactJS** (frontend) and **.NET** (backend).  

- building a multi‑layered .NET backend  
- building a ReactJS frontend consuming an API  
- simple flight search workflow  
- clean architecture and best practices  
- full‑stack integration

---

## Features

### ✅ Flight Search
- Search flight prices by:
  - origin airport
  - destination airport
  - departure date

### ✅ ReactJS Frontend
- Modern UI built with ReactJS  
- Fetches data from .NET API  
- Responsive user interactions

### ✅ .NET Backend
- Provides REST API endpoint(s) for flight search  
- Handles request validation  
- Can be extended to integrate real airline APIs  
- Solution file: `FlightSearch.sln`  
- Backend project: `FlightSearch/`

---

## Technologies Used

### Frontend
- ReactJS  
- JavaScript  
- npm / node  
- Fetch API / Axios (depending on your implementation)

### Backend
- .NET Framework / .NET Core (based on the solution in repo)  
- C#  
- ASP.NET Web API / MVC structure  
- JSON serialization  

### Other
- Visual Studio  
- npm package system  
- GitHub for source control  

---

## Project Structure

```
FlightSearch/
│
├── FlightSearch/          # .NET backend project
├── node_modules/          # React dependencies
├── package.json           # React package metadata
├── package-lock.json
├── FlightSearch.sln       # Visual Studio solution
├── KING ICT - .NET stručno testiranje.pdf
```

---

## Getting Started

### Prerequisites
- .NET SDK  
- Visual Studio or VS Code  
- Node.js + npm  

### Run Backend (.NET)
```
Open FlightSearch.sln in Visual Studio
Restore NuGet packages
Run the project (IIS Express)
```

### Run Frontend (ReactJS)
```
npm install
npm start
```

The frontend will launch on `http://localhost:3000`  
The backend will run on its configured localhost port.

---

## Possible Extensions

- Real API integration (Skyscanner, Tequila, Amadeus…)  
- Add multi‑city search  
- Add return flights  
- Add filters (price, duration, airline…)  
- Deployment to Azure / Vercel  
- Add authentication (JWT)  

---

## Purpose of the Project

This project was built as part of a technical exercise and as a portfolio demonstration of:

- full‑stack development (React + .NET)  
- API consumption  
- frontend‑backend communication  
- basic flight search logic  

It is ideal as evidence of software engineering skills in:

- C#  
- .NET Web API  
- ReactJS  
- Integration work  
- Multi‑layered application design  

---

## Overview

FlightSearch is a simple travel search application that allows users to query prices of low‑cost airline flights.  
It integrates a .NET backend service with a ReactJS user interface to provide an interactive and responsive flight search experience.

