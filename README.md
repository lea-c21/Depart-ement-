# Mon Départ(ement) 🗺️

A web application to help people choose where to live in France 
by exploring socio-economic and cultural data by department.

## About the project

Most housing platforms focus only on properties. 
**Mon Départ(ement)** takes a different approach: instead of filtering 
by apartment type, users can filter by socio-economic environment 
to find not just a home, but a place that truly fits their lifestyle.

## Features

- Interactive map of France
- Department-level socio-economic indicators (cost of living, 
  average income, cultural amenities...)
- Personalized filtering based on user criteria
- Detailed department profile pages

## Tech stack

- **Frontend:** HTML, CSS
- **Backend:** PHP
- **Database:** SQL (MySQL via WAMP)
- **Data source:** [data.gouv.fr](https://www.data.gouv.fr)

## Project structure
```
├── accueil.html       # Home page with interactive map
├── apropos.html       # About page
├── carte.html         # Interactive France map
├── contact.html       # Contact page
├── criteres.php       # User criteria filtering
├── bd.php             # Database connection
├── basedonnee.sql     # Database schema
├── script.sql         # SQL scripts
├── style.css          # Main stylesheet
└── style1.css         # Secondary stylesheet
```

## Database

The database contains socio-economic indicators per French department 
sourced from open government data (data.gouv.fr), including:
- Average annual income
- Cost of living indicators
- Cultural venues and amenities

## Authors

Group project — Licence MIASHS, Université Paul-Valéry Montpellier (2025)