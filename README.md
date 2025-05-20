# Belly-Button-Challenge
![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/crypto%20squish.jpg)

# Belly Button Biodiversity Dashboard

An interactive web dashboard that visualizes microbiome data collected from human belly buttons. Users can select a test subject from a dropdown menu to dynamically update a bar chart, bubble chart, and demographic info panel.

![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/crypto%20squish.jpg)

![HQ graphic](https://github.com/Lanceowesalot/CryptoClustering/blob/main/images/crypto%20squish.jpg)

---

##  Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Tools and Technologies Used](#tools-and-technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)
- [References](#references)

---

##  Project Overview

This project provides an interactive dashboard that allows users to:
- Select a test subject by ID
- View the top 10 bacteria cultures found in their belly button
- Analyze the overall bacterial makeup through a bubble chart
- Examine demographic metadata for each sample



---

##  Objectives

- Visualize complex biological data interactively
- Practice data fetching and filtering with D3.js
- Create responsive, data-driven charts with Plotly
- Demonstrate the power of front-end visual analytics


---

##  Dataset

- **Source**: [Belly Button Biodiversity Data](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)
- **Contents**:
  - `samples`: OTU IDs, labels, and values per subject
  - `metadata`: Subject demographics such as age, location, etc.
  - `names`: Array of subject IDs

---

##  Tools and Technologies Used

- **Languages**: JavaScript, HTML
- **Libraries**: D3.js, Plotly.js, Bootstrap 5
- **Hosting**: Local or static web hosting (e.g., GitHub Pages)

---

##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/belly-button-biodiversity.git
   ```
2. Navigate to the project folder:
   ```bash
   cd belly-button-biodiversity
   ```
3. Open `index.html` in your web browser.

> **Note**: No server or Python backend is needed. All data is loaded from a public JSON URL.

---

##  Usage

- Open the `index.html` file in any modern browser.
- Select a test subject from the dropdown menu.
- Watch the charts and metadata panel update accordingly.

---

##  File Structure

```
.
├── index.html              # Main HTML page
├── static/
│   └── js/
│       └── app.js          # Main JS script for fetching and visualizing data
├── README.md               # Project documentation
```

---

##  Key Findings

- Each subject has a unique bacterial signature.
- Some OTUs are commonly found across multiple subjects.
- The bubble chart helps reveal the overall microbial diversity at a glance.
- The top 10 bacteria cultures differ in both composition and abundance between individuals.

---

##  Conclusion

This project demonstrates how data visualization tools like D3 and Plotly can be used to create insightful, interactive visualizations for scientific data. The dashboard makes it easy for users to explore and interpret complex datasets without needing to write code.

---
## References

•	Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.

•	Data Source (Credits): the dataset is loaded from: https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json

•	D3.js: Documentation – JavaScript library for producing dynamic, interactive data visualizations: retrieved from https://d3js.org/what-is-d3

•	ChatGPT: Used for brainstorming, clarification, and coding assistance

•	Plotly.js: Documentation – Open-source graphing library for JavaScript: retrieved from https://plotly.com/javascript/

•	GitHub Pages: Documentation – Hosting service for static websites directly from GitHub repositories: retrieved from https://docs.github.com/en/pages

•	HTML Cheat Sheet: retrieved from htmlcheatsheet.com

•	 Class activites were used as examples for coding, as well as, ChatGPT was used for conceptual support and README format




