# Incarceration Trends Visualization

## Project Title
**The Long Count: Visualizing 50+ Years of Incarceration Trends in the United States**

---

## Project Overview

This project is an interactive scrollytelling visualization exploring incarceration trends across the United States at the county level. Using over five decades of data from the Vera Institute of Justice, the visualization enables users to examine how incarceration rates vary across geography, race, gender, and custody type.

Rather than relying on national averages, the project highlights county-level variation to reveal how incarceration outcomes differ across local communities. The experience combines guided narrative storytelling with interactive exploration, allowing users to transition seamlessly between explanatory sections and free-form analysis.

Developed for CMSC471: Introduction to Information Visualization at the University of Maryland, the project focuses on combining storytelling, interaction, and data exploration into a single cohesive experience.

---

## Live Demo

The project can be accessed through GitHub Pages:

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

This project uses the **Vera Institute of Justice Incarceration Trends Dataset**, which contains incarceration statistics for over 3,000 U.S. counties across multiple decades.

The dataset includes:
- Jail population totals
- Jail rates per 100,000 residents
- Prison population rates
- Racial incarceration breakdowns
- Gender incarceration breakdowns
- Pretrial vs. sentenced custody information
- Urbanicity classifications

### Why This Dataset?

This dataset is large and complex enough to warrant an interactive visualization because:
- It spans more than five decades of historical data
- It contains thousands of counties and multiple geographic scales
- It combines several dimensions simultaneously, including race, gender, geography, custody type, and time
- National averages often hide substantial county-level disparities

---

## Key Insights

The visualization reveals several important patterns in incarceration data across the United States:

- Incarceration rates increased substantially across many U.S. counties from 1970 through the early 2000s
- Large racial disparities in incarceration rates persist across many regions
- County-level incarceration rates vary significantly even within the same state
- Rural counties frequently exhibit unexpectedly high incarceration rates
- Pretrial detention represents a significant portion of jail populations in many counties
- Female incarceration rates increased considerably over time in many regions

---

## Features

### Interactive U.S. Map
- County-level incarceration visualization
- State and county drill-down exploration
- Dynamic color encoding based on incarceration rates

### Scrollytelling Narrative

The project guides users through multiple thematic sections, including:
- The incarceration boom
- Racial disparities
- State-level variation
- Rural incarceration
- Pretrial detention
- Gender trends
- Post-2008 incarceration decline

### Interactions
- Hover tooltips
- Zoom and pan navigation
- Click-to-drill-down exploration
- Animated timeline playback
- Interactive year slider
- Trend charts over time
- Category tabs for race, gender, custody type, and jail vs. prison comparisons

### Statistical Panels
- Jail population totals
- Jail rates
- Racial disparity comparisons
- Gender comparisons
- Custody-type donut charts
- County ranking lists
- Urbanicity breakdowns

---

## How to Use

- Scroll through the narrative chapters to explore major incarceration trends
- Hover over states and counties to view incarceration statistics
- Click states to drill down into county-level data
- Click counties to view detailed historical trends
- Use the year slider to explore incarceration changes over time
- Switch between category tabs to compare race, gender, custody type, and incarceration type
- Use the “Return to Story” button to return to the guided narrative experience

---

## Visual Design Decisions

### Color Encoding

The visualization uses a dark-to-orange sequential color scale:
- Darker colors represent lower incarceration rates
- Brighter orange tones represent higher incarceration rates

The scale remains fixed across years to support accurate temporal comparison.

### Layout

The interface uses a split-screen layout:
- Left side: persistent interactive map
- Right side: narrative content or statistical panels

This structure supports both guided storytelling and exploratory analysis.

### Interaction Techniques

The project incorporates:
- Scrollytelling for guided explanation
- Zoom and pan for spatial exploration
- Hover tooltips for contextual information
- Drill-down interactions for detail-on-demand analysis
- Timeline animation for temporal comparison

### Alternatives Considered

We considered:
- Traditional dashboard layouts
- Static infographic-style presentations
- Separate disconnected charts

We ultimately chose a scrollytelling structure because it better integrates narrative explanation with interactive exploration.

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
└── README.md
```

---

## Acknowledgements

### Data Source
- Vera Institute of Justice — Incarceration Trends Dataset

### Geography Data
- us-atlas / TopoJSON by Mike Bostock

### Libraries
- D3.js
- TopoJSON Client

### Design Inspiration
- Harry Stevens’ scrollytelling visualizations
- Explorable explanations
- Observable notebook layouts

---

## Team Contributions

### Ian Henry
- Led the overall architecture and visualization design
- Implemented core D3.js visualizations and interaction logic
- Designed and developed the scrollytelling experience
- Processed and managed incarceration datasets
- Optimized rendering performance for large county-level data
- Integrated charts, transitions, and interactive components

### Chan Park
- Assisted with D3.js visualization logic and timeline controls
- Assisted with debugging, testing, and final application refinement
- Managed GitHub repository setup and GitHub Pages deployment
- Contributed to README documentation and project write-up
- Gathered and incorporated feedback during development discussions
- Reviewed implementation consistency and application stability

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

AI tools were used to:
- Brainstorm interaction ideas
- Debug JavaScript and D3.js issues
- Refine documentation and written content

All generated code and writing were reviewed, modified, and integrated by the team.