# Incarceration Trends Visualization

## Project Title
**The Long Count: Visualizing 50+ Years of Incarceration Trends in the United States**

---

## Project Overview

This project is an interactive scrollytelling visualization exploring incarceration trends across the United States at the county level. Using over five decades of data from the Vera Institute of Justice, the visualization allows users to explore how incarceration rates differ across regions, racial groups, genders, and custody types.

Rather than relying on national averages, this project focuses on county-level variation to show how incarceration policies and outcomes differ dramatically depending on local conditions. The visualization combines explanatory narrative sections with interactive exploration tools, allowing users to transition from guided storytelling into free-form data exploration.

The project was created for CMSC471: Introduction to Information Visualization at the University of Maryland.

---

## Live Demo

The project can be accessed directly through the live GitHub Pages site:

https://cpark49.github.io/CMSC471-FinalProject/

---

## GitHub Repository

https://github.com/cpark49/CMSC471-FinalProject

---

## Team Members

- Ian Henry
- Chan Park

---

## Dataset

### Primary Dataset

The project uses the **Vera Institute of Justice Incarceration Trends Dataset**, which contains incarceration statistics for over 3,000 U.S. counties across multiple decades.

The dataset includes:
- Jail population
- Jail rates per 100,000 residents
- Prison population rates
- Racial incarceration breakdowns
- Gender incarceration breakdowns
- Pretrial vs sentenced custody information
- Urbanicity classifications

### Why This Dataset?

The dataset is large and complex enough to warrant an interactive visualization because:
- It spans over five decades of historical data
- It contains thousands of counties
- Multiple dimensions exist simultaneously (race, gender, custody type, geography, time)
- National trends alone hide large county-level disparities

---

## Features

### Interactive U.S. Map
- County-level incarceration visualization
- State drill-down exploration
- County drill-down exploration
- Dynamic color scaling

### Scrollytelling Narrative

The project guides users through multiple thematic sections:
- The incarceration boom
- Racial disparities
- State-level variation
- Rural incarceration
- Pretrial detention
- Gender trends
- Post-2008 incarceration decline

### Interactions
- Hover tooltips
- Zoom and pan
- Click-to-drill-down navigation
- Animated timeline playback
- Interactive year slider
- Trend charts over time
- Category tabs (racial, gender, custody, jail vs prison)

### Statistical Panels
- Jail population totals
- Jail rates
- Racial disparity bars
- Gender comparisons
- Custody-type donut charts
- County ranking lists
- Urbanicity breakdowns

---

## Visual Design Decisions

### Color Encoding

The primary map uses a dark-to-orange sequential color scale:
- Dark colors represent lower incarceration rates
- Bright orange represents higher incarceration rates

The scale remains fixed across years to support accurate temporal comparison.

### Layout

The interface uses a split-screen design:
- Left side: persistent interactive map
- Right side: narrative text or statistics panel

This structure supports both storytelling and exploratory analysis.

### Interaction Techniques

We used:
- Scrollytelling for guided explanation
- Zoom/pan for spatial exploration
- Hover tooltips for contextual information
- Drill-down interactions for detail-on-demand
- Timeline animation for temporal analysis

### Alternatives Considered

We considered:
- Traditional dashboards
- Static infographic layouts
- Multiple separate charts instead of integrated exploration

We ultimately chose a scrollytelling structure because it better combines narrative explanation with interactive discovery.

---

## Technologies Used

- JavaScript
- D3.js
- TopoJSON
- HTML5
- CSS3

---

## File Structure

```text
CMSC471-FinalProject/
│
├── index.html
├── data/
│   ├── incarceration_trends_county.csv
│   └── incarceration_trends_state.csv
│
├── README.md
└── assets/
```

## Acknowledgements

### Data Source
- Vera Institute of Justice — Incarceration Trends Dataset

### Geography Data
- us-atlas / TopoJSON by Mike Bostock

### Libraries
- D3.js
- TopoJSON Client

### Design Inspiration
- Harry Stevens' scrollytelling visualizations
- Explorable explanations
- Observable notebook layouts

---

## Team Contributions

### Ian Henry
- Led the overall development of the project architecture and visualization design
- Implemented core D3.js visualization components and interaction logic
- Designed and developed the scrollytelling experience and coordinated transitions
- Processed and managed the incarceration datasets
- Optimized map rendering and performance for large county-level data
- Helped integrate charts, tooltips, and interactive components

### Chan Park
- Assisted with D3.js visualization logic and timeline controls
- Assisted with debugging, testing, and final refinement of the application
- Managed GitHub repository setup and GitHub Pages deployment
- Contributed to README documentation and project write-up
- Gathered and incorporated feedback during team discussions and development reviews
- Reviewed implementation consistency and helped ensure application stability


---

## Development Process

The project was developed over approximately 5–6 weeks.

### Estimated Total Development Time
- Approximately 80–120 people-hours

### Most Time-Consuming Tasks
- Processing large county-level datasets
- Synchronizing interactions across views
- Designing the scrollytelling experience
- Managing map performance with thousands of counties
- Implementing coordinated transitions and animations

---

## AI Usage

We used AI tools to:
- Brainstorm interaction ideas
- Debug JavaScript and D3.js issues
- Refine documentation

All generated code and writing were reviewed, modified, and integrated by the team.