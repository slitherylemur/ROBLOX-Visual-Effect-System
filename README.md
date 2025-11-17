# Project Timeline - Gantt Chart

```mermaid
gantt
    title Visual Effect System for Roblox - Dissertation Timeline
    dateFormat YYYY-MM-DD

    section Task 1: Design
    System Architecture Design          :t1a, 2025-01-12, 4d
    Effect Data Format Schema           :t1b, after t1a, 3d
    UI Mockups & Timeline Editor Design :t1c, after t1b, 4d

    section Task 2: Plugin Editor Implementation
    Plugin Infrastructure               :t2a, after t1c, 5d
    Timeline & Keyframe System          :t2b, after t2a, 7d
    Asset Management Functionality      :t2c, after t2a, 6d
    Real-time Preview Capabilities      :t2d, after t2b, 5d
    Animation Engine Integration        :t2e, after t2c, 6d

    section Task 3: Export & Runtime Systems
    Effect Serialization Mechanism      :t3a, after t2d, 5d
    Runtime API Development             :t3b, after t3a, 6d
    Runtime Effect Loader               :t3c, after t3b, 5d

    section Task 4: Functional Testing
    Design Test Plans                   :t4a, after t2e, 3d
    Execute Functional Tests            :t4b, after t3c, 4d
    Document Issues & Fix Critical Bugs :t4c, after t4b, 4d

    section Task 5: User Testing
    Recruit Participants (4-5 users)    :t5a, after t4a, 5d
    Prepare Testing Materials & Tasks   :t5b, after t5a, 3d
    Conduct User Testing Sessions       :t5c, after t4c, 7d
    Semi-structured Interviews          :t5d, after t5c, 3d
    Data Analysis & Identify Patterns   :t5e, after t5d, 5d

    section Task 6: Refinement
    Implement Improvements from Testing :t6a, after t5e, 7d
    Final Bug Fixes & Polish            :t6b, after t6a, 4d

    section Dissertation Write-up
    Technical Documentation             :doc1, after t3b, 21d
    Results & Analysis Writing          :doc2, after t5e, 7d
    Final Editing & Proofreading        :doc3, after doc2, 5d
    Submission Preparation              :doc4, after t6b, 2d

    section Milestones
    Design Complete                     :milestone, after t1c, 0d
    Implementation Complete             :milestone, after t3c, 0d
    Testing Complete                    :milestone, after t5e, 0d
    Final Submission                    :milestone, 2025-03-31, 0d
```

## Key Dates
- **Start Date**: January 12, 2025
- **Design Complete**: ~January 23, 2025
- **Implementation Complete**: ~February 28, 2025
- **Testing & User Evaluation Complete**: ~March 19, 2025
- **Final Submission**: March 31, 2025

## Task Breakdown (Based on Dissertation Section 3.2 & 3.3)

### Task 1: Design System Architecture and UI (~11 days)
- System architecture documentation
- Effect data format schema
- UI mockups (timeline editor, asset management, preview controls)
- **Requirements**: FR-1, FR-1.1, FR-1.2, FR-2, FR-3, FR-4, NFR-1

### Task 2: Implement Plugin Editor (~29 days)
- Plugin infrastructure using Roblox Plugin API
- Timeline-based animation interface with keyframes
- Asset management system (ParticleEmitters, Beams, Trails, Sounds)
- Real-time preview capabilities
- Animation engine with TweenService integration
- **Requirements**: FR-1 through FR-3.4, NFR-1, NFR-1.1

### Task 3: Implement Export and Runtime Systems (~16 days)
- Effect serialization to ModuleScript format
- Runtime API for effect instantiation
- Runtime loader for executing effects during gameplay
- **Requirements**: FR-4, FR-4.1, FR-5 through FR-5.3, NFR-2

### Task 4: Develop and Execute Functional Tests (~11 days)
- Design comprehensive test plans with traceability to requirements
- Execute manual tests systematically
- Document results and identify issues requiring remediation
- **Requirements**: All FR and NFR requirements

### Task 5: Conduct User Testing and Analysis (~23 days)
- Recruit 4-5 representative Roblox developers
- Prepare realistic effect creation tasks
- Conduct observation sessions with think-aloud protocol
- Perform semi-structured interviews
- Systematic data analysis to identify patterns and recommendations
- **Requirements**: NFR-1, NFR-1.1

### Task 6: Implement Improvements Based on Evaluation (~11 days)
- Address functional deficiencies from testing
- Implement usability improvements from user feedback
- Prioritize by severity and impact
- Document all modifications

### Dissertation Write-up (Parallel & Final Stages)
- Technical documentation (runs parallel to implementation)
- Results and analysis writing (after user testing)
- Final editing and proofreading
- Submission preparation
