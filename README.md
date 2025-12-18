# Teaching Participatory ER Modeling with GARLIC

This repository contains **example teaching materials** for learning and teaching
**participatory Entity–Relationship (ER) modeling** using **GARLIC** — a
workshop-based educational methodology that adapts participatory design principles,
including the **ONION framework**, into a classroom setting.

The materials are designed to help students experience ER modeling as a
**socio-technical practice**, where data models are shaped by multiple perspectives
and where participatory success can be **explicitly validated**.

This repository accompanies the paper:

> *Seasoning Data Modeling Education with GARLIC: A Participatory Co-Design Framework*  
> TODO: add paper link, add bib for those who wants to cite.

---

## What Is GARLIC?

GARLIC (Generalized, Accessible, RelationaL, Inclusive Co-Design) is an
**educational methodology** for teaching participatory ER modeling through a
**structured workshop**.

It operationalizes participatory modeling by combining:

- Scenario framing  
- Role-based perspective taking  
- ONION participatory stages  
- Explicit validation through participant voices  

Rather than asking *“Is the ER diagram technically correct?”*, GARLIC asks:

> **“Which voices shaped this model, and which were lost?”**

---

## Core Teaching Materials

The workshop is built around **four types of cards**:

1. **Scenario Cards**  
2. **Role Cards**  
3. **ONION Stage Cards**  
4. *(Optional)* Facilitation & Timing Cards  

Each card type serves a distinct pedagogical function and is **visually
distinguishable by color**.

---

## Card Design and Color Coding

All cards are **color-coded** to reduce cognitive load and to make transitions
between activities explicit during facilitation.

A typical color scheme is:

- **Scenario Cards** — one color (e.g., yellow)  
  *Define the shared design context*

- **Role Cards** — another color (e.g., blue)  
  *Represent stakeholder voices*

- **ONION Stage Cards** — a third color (e.g., orange or red)  
  *Structure the participatory process*

Color is not decorative; it functions as a **pedagogical signal** that helps
participants recognize whether they are framing, advocating, or coordinating.

---

## 1. Scenario Cards

### What They Are
A **Scenario Card** defines the shared design space for the workshop.

It describes:
- The system to be designed
- The institutional or social setting
- The central tension (e.g., access vs. fairness)

### Example Scenario
> *Design a system capable of tracking registration for bachelor courses.  
> The system automatically enrolls students and decides who gets access to
> specific courses.*

### How to Use
- Exactly **one Scenario Card** per workshop  
- Introduced at the very beginning  
- Visible throughout the session  
- Never modified during the workshop  

The Scenario Card acts as a **stable anchor** against which all modeling decisions
are justified.

---

## 2. Role Cards (Voices)

### What They Are
Each **Role Card** represents a **voice** in the design process.
Roles are **not personas**; they are **advocacy positions**.

Each Role Card includes:
- **VOICE** — a non-negotiable claim  
- Primary concerns  
- What the role advocates for  
- Key questions the role raises  
- A validation check  

### Example Voice
> “My past grades should not permanently block my future opportunities.”

### Why They Matter
Role Cards make participation **traceable**.

Participatory success is validated by asking:

> *“Where is this voice represented in the ER model?”*

If a voice cannot be located in an entity, relationship, constraint, or attribute,
the participatory process is considered **incomplete**, not incorrect.

### How to Use
- One Role Card per participant  
- Participants argue **from the role**, not personal opinion  
- Roles remain fixed throughout the workshop  
- Role Cards are reused during validation  

---

## Mandatory vs. Optional Role Cards

For each scenario, GARLIC distinguishes between:

### Mandatory Role Cards
A minimal set of roles that surface the **core tensions** of the scenario.

Mandatory cards ensure:
- Multiple perspectives are present  
- Participatory validation is possible  
- The task does not collapse into technical modeling  

Without mandatory Role Cards, the activity becomes standard requirements gathering.

---

### Optional (Extra) Role Cards

Instructors may introduce **additional Role Cards** to increase complexity.

Adding extra Role Cards:
- Introduces new voices and power asymmetries  
- Increases negotiation and trade-offs  
- Makes validation more challenging and realistic  

For example, in the course registration scenario:
- A minimal setup might include 4 roles
- An advanced setup might add:
  - A student with low GPA (*Voice of Second Chances*)
  - A student with accessibility needs
  - A department-level policy role

Each added Role Card adds a **voice that must be preserved** in the final model.

---

## 3. ONION Stage Cards (Participatory Framework)

### What They Are
ONION Stage Cards represent the **participatory process**, adapted from the ONION
framework for educational use.

Each card defines:
- Stage goal  
- Participant activity  
- Expected output  

### Typical Stages (Simplified)
While ONION originates as a multi-layer participatory framework, GARLIC adapts it
into clear educational stages, for example:

1. **Observe** — explore the scenario and stakeholder context. In GARLIC this means being familarized with Scenario and Role cards.
2. **Nurture** — support and maintain stakeholder perspectives as they are articulated. This is a main activity, here participants start discussions and drawing ideas.
3. **Integrate** — combine perspectives into shared concepts and relationships. A technical specialist transforms drafts into initial ER model.
4. **Optimize** — refine the model through negotiation and trade-offs. Initial ER model is shown to participants and they revisit if their voices are represented.
5. **Normalize** — consolidate the outcome into a stable, shared representation. A technical specialist confirms that after previous stages ER model remains technically sound.

Stages are revealed **one at a time** and may be revisited.

---

## How Many People Do You Need?

### Minimum Viable Setup
- **3 participants**, 1 facilitator, 1 technical consultant (for stages that requires drafting simplified ER models, this can also be done by one of participants with this role as a dedicated responsibility)
- Such seminar may last from 60 to 120 minutes depending on the complexity of the scenario.

### Recommended Setup
- **3-5 participants**  
- One Role Card per person  
- Enables meaningful conflict and validation  

### Large Classes
- Run parallel groups  
- Same Scenario Card, different Role Card combinations  
- Compare resulting ER models 

---

## Workshop Flow (High Level)

1. Introduce the **Scenario Card**
2. Assign **Role Cards**
3. Individual reflection from role perspective
4. Progress through **ONION stages**
5. Construct a shared ER model
6. **Validate** by returning Role Cards:
   > *“Where is your voice in the model?”*
7. If voices are missing, revisit earlier stages

---

## Adapting Complexity by Student Seniority

GARLIC supports **progressive complexity** without changing the core methodology.

- **Introductory / Bachelor level**
  - Fewer Role Cards (3-4)
  - Clear tensions
  - Focus on traceability and participation
  - Simplified scenarious

- **Advanced / Master level**
  - Additional Role Cards
  - Conflicting and overlapping voices
  - Emphasis on negotiation

- **Graduate / Professional settings**
  - Many Role Cards
  - Ambiguous priorities
  - Strong focus on validation and iteration
  - Intentional missing voices on Integrate ONION stage in order to trigger revisiting previous stages of the methodology

---

## What This Teaches

Students learn:
- That ER models embed values and priorities from people who will use the system, but also from people who will be indirectly influenced by the system
- That `requirements` are negotiated, not given  
- How automation can reinforce or reduce inequality  
- How to validate models beyond technical correctness  

---

## What This Repository Is (and Is Not)

+ A **teaching toolkit**
+ A **replicable workshop methodology**
+ An **educational operationalization of participatory design**

- Not a full ONION specification  
- Not a replacement for ER theory  
- Not a single `correct` modeling recipe  

---

## License and Reuse

Materials are provided for **educational and research use**.
You are encouraged to adapt scenarios and roles to your local context.

If you use or adapt GARLIC, please cite the accompanying paper.

---

## Citation

TODO
