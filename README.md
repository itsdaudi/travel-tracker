# Travel Journal Web Application

A modern, responsive web application for tracking and remembering all the amazing places you've visited around the world.

![Travel Journal Screenshot](screenshot.png)

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

## Business Logic (TDD Implementation)

### Place Object
The application follows Test-Driven Development principles with a robust `Place` class:

```javascript
class Place {
    constructor(location, landmarks, timeOfYear, year, notes, rating, tags)
}
Travel Journal
├── Place Class (Business Logic)
│   ├── Properties with validation
│   ├── Search methods
│   └── Filter methods
├── TravelJournal Class (Data Management)
│   ├── CRUD operations
│   ├── Search/Filter functionality
│   └── LocalStorage integration
└── UI Layer
    ├── Form handling
    ├── Dynamic rendering
    └── Event management
    
## 2. **LICENSE** (Create this file in your project folder)

```text
MIT License

Copyright (c) 2024 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.