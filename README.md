# Travel Journal Web Application

A modern, responsive web application for tracking and remembering all the amazing places you've visited around the world.

## Features

### 📝 Add Travel Destinations

- **Location**: Track cities, countries, or specific places
- **Landmarks**: List multiple attractions with comma separation
- **Time of Year**: Select from Spring, Summer, Fall, or Winter
- **Year**: Record when you visited
- **Rating**: 1-5 star rating system
- **Notes**: Add detailed memories and experiences
- **Tags**: Categorize with custom tags

### 🔍 Search & Filter

- **Real-time search**: Search across locations, landmarks, notes, and tags
- **Rating filter**: Filter by minimum star rating
- **Season filter**: Filter by time of year
- **Interactive UI**: Click any place to view full details

### 💾 Data Management

- **Local Storage**: All data persists in your browser
- **CRUD Operations**: Create, Read, Update, Delete functionality
- **Sample Data**: Pre-loaded with example destinations
- **Statistics**: Track total places and average ratings

### 🎨 Modern Design

- **Responsive Layout**: Works on desktop, tablet, and mobile
- **Clean Interface**: Intuitive user experience
- **Interactive Elements**: Hover effects, animations, and visual feedback
- **Star Rating System**: Visual 5-star rating input

## Project Structure

```
travel-tracker/
├── index.html          # Main HTML file
├── working.html        # Working/draft HTML file
├── README.md           # This file
├── license             # MIT License file
└── ima/                # Image assets directory
```

## Business Logic (TDD Implementation)

### Place Object

The application follows Test-Driven Development principles with a robust `Place` class:

```
javascript
class Place {
    constructor(location, landmarks, timeOfYear, year, notes, rating, tags)
}
```

### Class Architecture

- **Place Class** (Business Logic)
  - Properties with validation
  - Search methods
  - Filter methods

- **TravelJournal Class** (Data Management)
  - CRUD operations
  - Search/Filter functionality
  - LocalStorage integration

- **UI Layer**
  - Form handling
  - Dynamic rendering
  - Event management

## Getting Started

1. Clone or download the repository
2. Open `index.html` in your web browser
3. Start adding your travel destinations!

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- LocalStorage API

## License

This project is licensed under the MIT License - see the `license` file for details.
