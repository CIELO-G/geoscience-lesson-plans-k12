# Lesson Plan: Advanced CAD Features — Hole, Shell, Split, Combine, Delete Face, Thicken/Offset, Assembly  
*(10th Grade — 5E Engineering Lesson)*

## Grade Level
10th Grade (Engineering / CAD)

## Duration
1–2 class periods

## Learning Objectives
Students will be able to:

- Understand how CAD features modify existing geometry
- Apply **Hole, Shell, Split, Combine, Delete Face, and Thicken/Offset** operations
- Explain the purpose of each feature in engineering design
- Create and modify parts that can later be used in **assemblies**
- Justify modeling decisions based on **design intent**

## Materials Needed

- Computers with CAD software (Autodesk Inventor, Fusion 360, SolidWorks, or equivalent)
- Projector to display example CAD models
- Starter CAD files or simple extrusion models
- Student worksheets for documenting observations
- Screenshot or screen-capture tool

---

# Engage

## Prompt / Phenomenon

Display two CAD images to the class:

- A **solid rectangular block with a cylindrical hole**
- The **same block after a shell operation**, creating a hollow interior

Ask students:

> **How could the solid block turn into a hollow part?**  
> **What CAD features might make that change?**

Allow students to make predictions about possible modeling steps.

### Time
5 minutes

### Purpose
Spark curiosity about how **CAD features transform geometry** and introduce the idea that complex engineering components are created through a sequence of simple modeling operations.

---

# Explore

## Guided Hands-On Stations

Students work **in pairs at CAD workstations**.

### Station A — Hole & Delete Face

Students begin with a **simple rectangular extrusion**.

Tasks:

1. Create a **sketch circle** on the top face.
2. Apply the **Hole feature** using diameter and depth parameters.
3. Experiment with **hole types**:
   - Simple
   - Counterbore
   - Countersink
4. Observe how the geometry changes depending on the hole settings.

Next:

- Use **Delete Face** on a selected face.
- Test the **Heal Remaining Faces** option.
- Observe how removing a face changes the topology of the part.

Students record:
- Feature used
- Key parameters
- Screenshot of the model before and after modification.

---

### Station B — Shell, Split, Combine, Thicken/Offset

Using the same base block:

**Shell**

- Apply the **Shell feature** to hollow the object.
- Remove one face to create an opening.
- Adjust wall thickness and observe the results.

**Split**

- Sketch a curve or plane on the model.
- Use **Split** to divide the solid into separate bodies.
- Keep both sides and observe the difference.

**Combine**

- Create a second solid body (cylinder or prism).
- Use **Combine** with:
  - Join
  - Cut
  - Intersect

Compare how each boolean operation modifies the model.

**Thicken / Offset**

- Create a thin surface or plate.
- Use **Thicken** or **Offset** to convert the surface into a solid body.

---

### Student Expectations

Each pair documents:

- The CAD command used
- Key dialog parameters they adjusted
- One screenshot showing **before and after geometry**

### Time
40 minutes

### Teacher Role

The teacher circulates through the stations and asks probing questions such as:

> What changed when you used the **Shell** command?  
> How did **Combine Cut** differ from **Combine Join**?  
> Why might engineers remove faces instead of rebuilding geometry?

Student observations are recorded for the class discussion.

---

# Explain

## Whole-Class Debrief

Invite several student pairs to present their models and explain:

- Which feature they used
- What settings they adjusted
- How the feature changed the shape

### Teacher-Led Questions

- How does **hole termination** determine whether a hole is blind or through?
- When would an engineer use a **counterbore** versus a **countersink**?
- How does **Shell** control wall thickness in a hollow component?
- What is the difference between **Split** and **Combine**?
- When should **Delete Face** be used instead of recreating geometry?

---

## Mini Lesson — Key CAD Feature Concepts

**Hole**

- Used to create precise cylindrical openings
- Includes options such as diameter, termination type, and fastener settings

**Shell**

- Converts a solid body into a hollow structure
- Controlled by wall thickness and selected faces to remove

**Split**

- Divides a part into multiple bodies using surfaces or sketches

**Combine**

- Performs Boolean operations between bodies:
  - Join
  - Cut
  - Intersect

**Delete Face**

- Removes geometry while optionally healing surrounding faces

**Thicken / Offset**

- Converts surfaces into solid geometry by adding thickness

### Connection to Assemblies

Explain how these features help prepare parts for **assemblies**, where components are placed and constrained together to simulate real mechanical systems.

### Time
20 minutes

---

# Elaborate

## Application Tasks

### Engineering Design Challenge

Students design **three simple parts** inspired by real mechanical components:

- A **linkage arm (clevis)**
- A **stepped shaft**
- A **rectangular mounting block with a through-hole**

Students must apply multiple CAD features such as:

- Hole
- Shell (if appropriate)
- Split
- Combine
- Thicken

Next, students assemble the parts:

- Place each component in an assembly environment
- Apply **constraints or joints** so the shaft connects the linkage to the block.

---

### Variation / Design Transfer

Students modify the linkage arm by converting it into a **lightweight shelled design**.

They must justify:

- Why a shell reduces weight
- How wall thickness affects strength.

---

### Extension for Advanced Students

Advanced students add:

- **Threaded holes**
- Standard **fasteners**
- Additional parametric constraints

### Time
1–2 class periods

---

# Evaluate

## Formative Assessment

### Exit Ticket

Students answer:

- One function of each feature:
  - Hole
  - Shell
  - Split
  - Combine
  - Delete Face
  - Thicken/Offset
- One engineering situation where each feature would be useful.

### Teacher Observation

While circulating, the teacher checks:

- Correct feature selection
- Proper parameter inputs
- Accurate geometry creation

---

## Summative Assessment

### Project Deliverables

Students submit:

- CAD model files
- Three rendered views (including an **isometric view**)
- A **one-page design rationale** describing which features were used and why
- Screenshot of assembly constraints applied

---

## Rubric Criteria

| Criteria | Weight |
|--------|--------|
| Correct application of CAD features | 30% |
| Accurate dimensions and parameters | 25% |
| Assembly functionality | 20% |
| Explanation and design reasoning | 15% |
| File organization and screenshots | 10% |

---

## Self-Assessment

Students complete a short reflection:

- Rate confidence using **Hole, Shell, Split, and Combine** (scale 1–4)
- Identify one concept they learned
- Identify one CAD skill they want to improve

---

## Teacher Feedback

Provide targeted comments on:

- Feature selection
- Modeling technique
- Adherence to engineering constraints
