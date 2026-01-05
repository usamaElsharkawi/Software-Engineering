# Software Development Processes and Methodologies

## Detailed Notes

### 1. The Power of Requirements

Requirements are the foundation of any software project. They serve as:

- **A Definition of Success:** Measurable goals to know when a project is done.
- **Communication Bridge:** Common ground between non-technical stakeholders and developers.
- **Cost Control:** Fixing a requirement error is significantly cheaper than fixing code.
- **Scope Protection:** Prevents "Scope Creep" by defining boundaries.

### 2. Requirements vs. Specifications

- **Requirements (User View):** Focuses on the problem and the "What/Why". Often written in plain, non-technical language.
- **Specifications (Developer View):** The technical "What" and "How". A precise, measurable translation of requirements for implementation.

### 3. Functional vs. Non-Functional Requirements (NFRs)

- **Functional:** The specific actions/features the system does (e.g., "User can login").
- **Non-Functional (The "-ilities"):** How the system behaves. Includes Performance, Scalability, Security, Usability, and Availability.
  - _Analogy:_ Functional is the engine/wheels of a car; Non-Functional is the speed, safety rating, and fuel efficiency.

### 4. WRSPM Model & The Success Equation

A formal model to bridge the gap between the real world and the machine.

- **W (World):** Facts/assumptions about the environment (Domain knowledge).
- **R (Requirements):** The desired state/goal in the real world.
- **S (Specifications):** The shared interface/behavior between the machine and the world.
- **P (Program):** The code written by developers.
- **M (Machine):** The hardware/platform (OS, CPU, etc.).

#### The Success Equation:

To solve the user's problem, we must prove:

1.  **Code Correctness:** $M, P \vdash S$ (The machine and program meet the spec).
2.  **Engineering Validity:** $W, S \vdash R$ (If the spec is met in this world, the requirement is satisfied).
3.  **Grand Success:** $W, M, P \vdash R$ (The whole system solves the real-world problem).
