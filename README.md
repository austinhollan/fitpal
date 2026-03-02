# FitPal — Fitness & Nutrition Tracker

A full-featured fitness and nutrition tracking app built as a single-file mobile-first web application.

## Features

### Workout Tracking
- Weightlifting with sets/reps/weight logging
- Cardio with distance, duration, and pace
- Bodyweight exercises
- Active workout overlay with rest timer
- Exercise form video links (curated YouTube guides for 30+ exercises)
- Workout templates (Push, Pull, Legs, Full Body, HIIT)
- Exercise history and PR tracking

### Nutrition
- Calorie and macro tracking (protein, carbs, fat)
- 203-item embedded USDA-sourced food database
- Live USDA FoodData Central API integration (300k+ foods)
- Barcode scanner via QuaggaJS + Open Food Facts
- Micronutrient panel (10 nutrients)
- Food quality indicators and scores
- Recipe builder
- Meal copying, multi-add, quick-add calories
- Macro pie chart
- Custom foods, recent/frequent tracking

### Meal Planning
- Weekly meal planner with day-by-day view
- Templates (Balanced, Bulk, Cut)
- USDA search in meal plan builder
- Share meal plans

### Progress
- Weight and body fat charts (Chart.js)
- Body measurements tracking
- Personal records

### Other
- Water tracker (8 glasses)
- Dark-first design (#0d0d0f background, #8aff00 green accent, #ff6b35 orange)
- Mobile-first (480px max width)
- 6-tab bottom navigation

## Tech Stack
- Vanilla HTML/CSS/JavaScript (single file)
- Chart.js (CDN) for progress charts
- Lucide Icons (CDN)
- QuaggaJS (CDN) for barcode scanning
- USDA FoodData Central API
- Open Food Facts API

## Getting Started
Simply open `index.html` in a browser or deploy to any static hosting.

## API Keys
The app uses the USDA FoodData Central API. Replace the API key in the source code with your own from [USDA FoodData Central](https://fdc.nal.usda.gov/api-key-signup.html).