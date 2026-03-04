# Lesson 03: Modeling Terrain with DEMs and CAD
*(10th Grade — Engineering & Geoscience 5E Lesson)*

## Grade Level
10th Grade (Engineering, Earth Science, or STEM)

## Duration
1–2 class periods

## Learning Objectives
Students will be able to:

- Explain how terrain elevation data can be converted into **Digital Elevation Models (DEMs)**
- Import and visualize terrain data using **GIS tools**
- Generate and interpret DEM surfaces from sampled elevation points
- Understand how engineers use terrain data for **infrastructure planning**
- Prepare terrain models for **3D CAD visualization or 3D printing**

## Materials Needed

- Computers with **QGIS installed**
- Sample **CSV elevation datasets** (latitude, longitude, elevation)
- DEM raster examples
- Projector to display terrain images and models
- Optional: 3D printer for exporting terrain models
- Step-by-step QGIS workflow guide

---

# Engage

## Phenomenon / Prompt

Display images showing:

- A **satellite image of Mount Rainier**
- A **3D terrain model generated from elevation data**

Ask students:

> **How can we turn a flat map or a set of elevation numbers into a 3D terrain model?**  
> **What information would engineers need before building a dam or placing a road in this landscape?**

### Think–Pair–Share (3 minutes)

Students work in pairs to list **three reasons why terrain sampling matters** for construction projects.

Possible responses may include:

- Foundation stability  
- Water inflow and reservoir capacity  
- Flood risks  
- Environmental impacts  
- Access for construction

### Time
10 minutes

### Purpose
Introduce the concept that **terrain data drives engineering decisions** and motivate students to explore how elevation data becomes a 3D model.

---

# Explore

## Hands-On Group Activity

Students work in small groups using **QGIS** to create and visualize terrain models.

### Step 1 — Import Elevation Data

Students import a **CSV file containing point coordinates and elevation values**.

Using QGIS:

- Open **Data Source Manager**
- Import the CSV as a **Delimited Text Layer**
- Visualize the points on a map

---

### Step 2 — Generate a DEM

Students convert the point dataset into a continuous terrain surface using interpolation methods such as:

- **TIN (Triangulated Irregular Network) interpolation**
- **Inverse Distance Weighting (IDW)**

This creates a **Digital Elevation Model (DEM)** raster representing terrain height.

---

### Step 3 — Visualize Terrain

Students apply visualization styles to the DEM:

- **Singleband pseudocolor** to show elevation gradients
- **Hillshade** to highlight terrain shape and slopes

Students analyze the resulting terrain surface.

---

### Teacher Prompts

While circulating, the teacher asks:

- Which areas appear **highest and lowest**?
- Where might **water naturally flow**?
- Which locations might be best for **construction or dam placement**?

---

### Materials & Setup

- Sample elevation CSV files
- QGIS software
- Short QGIS workflow guide
- One computer per group

### Time
30–40 minutes

---

# Explain

## Whole-Class Discussion

Students present their terrain visualizations and explain what they discovered.

### Key Concepts

**Point Data → Interpolation → DEM**

Explain how engineers convert **discrete elevation points** into a continuous terrain surface through interpolation methods.

**Interpolation Methods**

- **TIN:** Creates triangular surfaces between nearby elevation points  
- **IDW:** Estimates elevation based on nearby values

**Visualization Tools**

GIS tools allow users to apply:

- Color gradients for elevation
- Hillshade to simulate sunlight and terrain shadows

---

## Real-World Applications

Discuss how engineers use terrain models for:

- **Dam construction planning**
- **Flood risk assessment**
- **Transportation route planning**
- **Environmental monitoring**
- **Bathymetric mapping using autonomous boats**

Encourage students to use their DEM maps to identify:

- Steep slopes
- Water drainage paths
- Suitable building locations

### Time
15–20 minutes

---

# Elaborate

## Extension Activities

### Option A — CAD / 3D Printing

Students prepare their terrain model for **3D export**.

Steps include:

- Selecting a terrain extent
- Choosing an appropriate model scale
- Adjusting **vertical exaggeration**
- Exporting the DEM as an **STL file**

The STL model can then be:

- Visualized in CAD software
- Prepared for **3D printing**

This allows students to physically examine terrain geometry.

---

### Option B — Engineering Terrain Analysis

Students analyze their DEM to recommend a **dam location**.

They must consider:

- Foundation stability
- Reservoir capacity
- Sediment accumulation
- Environmental impact
- Accessibility

Students submit:

- Annotated terrain screenshots
- A short written explanation justifying their decision.

---

### Cross-Disciplinary Connections

Discuss how terrain and bathymetry data support:

- Environmental monitoring
- Water resource management
- Hazard mitigation
- Policy and infrastructure planning

### Time
1–2 class periods (optional extension)

---

# Evaluate

## Formative Assessment

### Exit Ticket

Students write a three-sentence response describing:

1. One step used to convert point data into a DEM  
2. One terrain factor important for dam placement  
3. One advantage of exporting DEMs into 3D models

### Teacher Observation

During the activity, the teacher checks:

- Correct import of elevation data
- Successful DEM generation
- Appropriate visualization settings
- Evidence-based terrain interpretation

---

## Summative Assessment

Students complete **one of the following projects**.

### Option 1 — DEM Workflow Demonstration

Students submit a **3-minute recorded screen walkthrough** showing:

- Importing elevation data
- Generating a DEM
- Applying visualization styles
- Preparing the terrain model for export

Students also submit a **one-page reflection** explaining how terrain analysis informs engineering decisions.

**Rubric**

- Technical accuracy — 40%  
- Interpretation of terrain — 30%  
- Presentation clarity — 20%  
- Environmental or ethical considerations — 10%

---

### Option 2 — Engineering Brief

Students prepare a **2–3 page engineering report** recommending a dam location using their DEM analysis.

The report should include:

- Annotated terrain maps
- Evidence supporting the chosen site
- Environmental considerations
- Monitoring recommendations

**Rubric**

- Use of DEM evidence — 40%  
- Application of terrain concepts — 30%  
- Clarity and citations — 20%  
- Environmental or policy considerations — 10%

---

## Self-Assessment

Students rate their confidence (1–4 scale) in:

- Using GIS tools to create DEMs  
- Interpreting terrain for engineering decisions  
- Preparing terrain models for CAD or 3D export

Students briefly justify **one rating** in a written sentence.

---

# Differentiation & Support

**Support for Beginners**

- Provide step-by-step QGIS instructions
- Offer pre-loaded datasets
- Allow students to focus only on visualization rather than interpolation

**Advanced Students**

- Compare multiple interpolation methods (TIN vs IDW)
- Analyze slope and watershed maps
- Prepare terrain models optimized for 3D printing

**Collaborative Learning**

Students work in small teams so they can support each other during GIS workflows.
