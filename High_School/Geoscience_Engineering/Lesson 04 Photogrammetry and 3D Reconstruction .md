# Lesson 4: Photogrammetry and 3D Reconstruction  
*Using Your Smartphone to Build Digital Models (10th Grade — 5E Lesson)*

## Grade Level
10th Grade (Engineering / STEM / Geoscience Applications)

## Duration
1 class period (50–60 minutes) or 2 shorter sessions + optional extension

## Learning Objectives
Students will be able to:

- Explain how **overlapping photographs** can be used to reconstruct 3D geometry
- Apply a repeatable **photo capture protocol** for photogrammetry
- Describe key ideas behind reconstruction: **feature matching** and **triangulation**
- Generate a basic 3D model using a smartphone app or desktop workflow
- Evaluate model quality and propose improvements through iteration
- Connect photogrammetry to real-world applications in archaeology, engineering, and disaster response

## Materials Needed

- Smartphones (1 per student or per team)
- Photogrammetry app (e.g., Polycam, Kiri Engine) or access to a desktop tool (e.g., COLMAP, Meshroom)
- A small object to scan (statue, rock, bench, classroom object)
- Stable lighting source (optional) and a neutral background (helpful)
- Internet access (if using cloud processing)
- Student capture log sheet (protocol + observations)
- Projector for showing example images and student outputs

---

# Engage

## Quick Phenomenon / Demo

Show students two images side-by-side:

- An “Actual” photograph of an object/structure (example: a stupa photograph)
- A “3D Model” rendering generated from photographs

Ask:

> **How could a pile of photos turn into this 3D model?**

Elicit student prior experiences with:
- phone cameras
- 3D photos
- scanning apps (e.g., Polycam)

Show a second motivating comparison (original vs replica / reconstruction example) to highlight real-world impact and why accurate 3D models matter.

## Driving Question

> **How can we use overlapping photos taken with a smartphone to create accurate 3D models useful for archaeology, engineering, or disaster response?**

### Time
5–7 minutes

### Purpose
Spark curiosity about how images become 3D data and set up the investigation around overlap and reconstruction.

---

# Explore

## Hands-On Investigation

Students form small teams (3–4). Each team selects a small object in the classroom or outdoors (e.g., statue, bench, rock) to scan.

### Photo Capture Protocol

Using smartphones and an agreed path, students capture a sequence of overlapping photos:

- Walk around the object at **two heights** (eye level and slightly above/below)
- Keep **focus and exposure steady**
- Aim for **strong overlap** between successive images
- Use **varied angles** and avoid large jumps in viewpoint
- Minimum: more than a couple images, but aim for **20–50 photos** for a solid reconstruction

Key capture tips to emphasize:

- Overlap matters more than “perfect” single photos
- Avoid motion blur (hold steady, pause if needed)
- Avoid reflections and shiny surfaces when possible
- Keep distance fairly consistent (don’t zoom in/out repeatedly)

### Model Generation

Teams choose one workflow:

- Upload images to a mobile photogrammetry app (e.g., Polycam or Kiri Engine), **or**
- Export images to a desktop pipeline (COLMAP, Meshroom) if available

### Documentation Expectations

Each team records:

- Number of photos captured
- Approximate overlap
- Distance to object
- Lighting conditions
- Any difficulties (glare, blur, missing angles, background clutter)

### Teacher Prompts (During Work Time)

- How many matching features do you see between images?
- Where do photos fail to align?
- What changes if you move closer or farther?
- Which angles are missing that might cause holes in the model?

### Time
50–60 minutes (or split into two shorter sessions)

---

# Explain

## Whole-Class Synthesis

### Mini-Lesson (Teacher-Led)

Clarify the core concepts behind photogrammetry:

- **Photogrammetry**: obtaining reliable information about objects/environments from photographs
- **Key principles**:
  - Overlapping images enable **feature matching**
  - Multiple viewpoints enable **triangulation** (estimating 3D position from intersecting lines of sight)
  - Camera settings and capture stability affect reconstruction quality
  - Post-processing converts matches into **point clouds** and then **meshes** (often with textures)

### Student Evidence Discussion

Teams share:

- Their capture protocol notes
- One screenshot of an initial model result (even if imperfect)

Facilitate student explanations:

- Which photos aligned well?
- Where did you get dense point coverage?
- Where did the model become noisy or incomplete?
- What capture choices likely caused those outcomes?

### Application Examples (Teacher Connection)

Show a few example use cases and discuss how photogrammetry outputs can support analysis beyond visualization:

- Archaeology / cultural heritage (digital twins for conservation)
- Paleontology / geomorphology (mapping tracks or terrain features)
- Engineering (geometry extraction; what additional data would be needed for structural analysis)
- Disaster response (rapid mapping of damage and hazards)

### Time
20–30 minutes

---

# Elaborate

## Extension / Application Tasks

Students complete a short “digital conservation” mini-project by choosing one option:

### Option A — Archaeology / Conservation

Create a textured 3D model of a campus historical object and write a short report explaining how a **digital twin** could aid conservation and documentation.

### Option B — Engineering / Structural Analysis Intro

Use the 3D model to identify geometric features and discuss what additional data would be needed for analysis (e.g., material properties, supports, loading conditions) for tasks such as vibration or structural evaluation.

### Option C — Citizen Science / Disaster Response

Propose a workflow to rapidly map local flood or storm damage using smartphone or drone photogrammetry. Include:

- strengths
- limitations
- ethical concerns (privacy, access, responsible sharing)

### Iteration (Engineering Design Cycle)

Students revise their capture plan based on what went wrong and improve the model:

- Re-capture images if feasible
- Re-run reconstruction
- Compare “before” vs “after” and explain what improved

### Cross-Curricular Product

Students prepare a 3–4 minute presentation including:

- a model screenshot or embedded viewer link
- their capture protocol
- limitations encountered
- one real-world application area (archaeology, paleontology, engineering, disaster response)

### Time
1–2 class periods (optional)

---

# Evaluate

## Formative Checks

### Exit Ticket

Students answer:

- List **three factors** that improve photogrammetry reconstruction
- Cite **one piece of evidence** from your team’s attempt (e.g., overlap helped alignment; glare caused noise)

### Observation Checklist

While circulating, the teacher checks:

- Did students capture overlapping images?
- Did they record camera/lighting conditions?
- Did they attempt iteration after failure?

---

## Summative Assessment (Project Rubric)

### Criteria

**Technical quality of model (30%)**
- completeness, level of detail, minimal holes/noise

**Process documentation (25%)**
- capture protocol (angles, overlap, settings), number of photos, and changes after iteration

**Scientific explanation (25%)**
- connects capture choices to principles (overlap, triangulation, camera stability/parameters)

**Application & reflection (20%)**
- presentation quality and a reasoned proposal for a real-world use case, including limitations and ethical considerations

---

## Self-Assessment

Students complete a short reflective rubric rating their team on:

- collaboration
- problem-solving
- effectiveness of iteration based on evidence

---

## Teacher Answer Key / Guidance (for Feedback)

Expected correct ideas include:

- **Overlap** improves feature matching and alignment between photos
- **Varied viewpoints** are needed for triangulation and to reduce holes
- **Stable exposure/focus** helps consistent matching
- **Good lighting** reduces noise; poor lighting increases blur/noise
- **Shiny or textureless surfaces** reduce identifiable features and can degrade reconstruction
