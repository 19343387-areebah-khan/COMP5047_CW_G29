# COMP5047 Applied Software Engineering  
## Group G29 – Week 10 Meeting Agenda & Minutes

**Date:** 25/11/25  
**Time:** 16:00–18:00 
**Location:** Google Meet  

**Attendees:**  
- David Gaman (19238600)  
- Aziz Hussein Boakye (19067039)  
- Areebah Khan (19343387)  
- Daniil Tkachenko (19323083)  

_All Present_

---

## Agenda
1. Consolidation of all work completed so far (Tasks 3, 4a, 4b).  
2. Final review of the integrated system architecture (Task 4b).  
3. Identify inconsistencies and naming issues across subsystems.  
4. Discuss updates required for each subsystem after integration.  
5. Begin Task 5(a) class diagrams and check alignment with architecture.  
6. Begin Task 5(b) sequence diagrams.  
7. Plan tasks for the coming week.

---

## Progress Since Last Meeting
- All subsystem diagrams for Task 4(a) have been completed.  
- The first integrated architectural model (Task 4b) has been created and shared.  
- Interface naming has mostly been aligned using the shared glossary.  
- Each member has selected a microservice for detailed design in Task 5.  
- GitHub folders are updated and everything from Task 4 is now in place.  
- Group chat used regularly to check diagrams and clarify interface dependencies.

---

## Discussion

### 1. Consolidation Review (Week 10 Focus)
We reviewed all previous work (Tasks 3, 4a, 4b) to check consistency:

- Use Case diagrams from Task 3 align with the case study.  
- All microservices in Task 4(a) now match the boundaries of each subsystem.  
- For Task 4(b), we went through the integrated diagram together and compared cross-subsystem interfaces.

During consolidation, a few issues were identified:

- Two subsystems had their own notification adapters, so these were merged into one shared component.  
- Some interface names were inconsistent across diagrams and need updating to a standard naming scheme.  
- A circular dependency appeared between the Student App and USU OS in the first draft, which has now been removed.  
- A missing required interface was identified in the Society subsystem (Daniil will add this).  
- Entity naming (e.g. UnionId, EventId, SocietyId) was standardised.

The lecturer mentioned that subsystem designs must be updated after integration, so we noted where edits are required.

### 2. Class Diagram Planning (Task 5a)
- Each member shared their early class diagram ideas.  
- Diagrams must reflect the integrated architecture, not earlier drafts.  
- Everyone recognised that some operations might need refining once sequence diagrams are modelled.

### 3. Behaviour Modelling (Task 5b)
- Sequence diagrams will focus on the behaviour inside each chosen microservice.  
- We agreed to include success paths and exceptional flows.  
- Will use alt and opt frames as required.

### 4. Areas Needing Improvement
From consolidation, we identified:

- A few microservices were too large and may need splitting when writing the class diagrams.  
- Some interface operations are missing from class diagrams and will need adding.  
- A few naming inconsistencies remain and need fixing before the final submission.

---

## Actions Agreed

### Fixes Based on Consolidation
- Merge duplicate notification components into one shared adapter.  
- Update all diagrams to use consistent interface names from the glossary.  
- Add the missing required interface to the Society subsystem.  
- Adjust subsystem boundaries where needed so they match the integrated model.  
- Review microservices to ensure they are not oversized before creating class diagrams.

### Task 5 Work
- Each member to complete a class diagram for their selected microservice (Task 5a).  
- Begin sequence diagrams once class diagrams are stable (Task 5b).  
- Write the accompanying component descriptions for 4(a)/4(b) based on the Week 10 lecture.  
- Make at least one GitHub commit this week for Task 5.

### GitHub & Workflow
- Keep diagrams organised inside the correct folders.  
- Commit changes incrementally to avoid losing history.

**Next Meeting:** Tuesday 02/12/25 at 17:00.

---

## Issues Raised
- Papyrus continues to run slowly; members reminded to save frequently.  
- Integrated architecture diagram is quite large, so packages will be used to keep it readable.  
- Sequence diagrams may reveal missing operations in class diagrams, so updates are expected.  
- Need to confirm with lecturer whether repository classes should appear in sequence diagrams.

---

**Prepared by:** Areebah  
**Date of Writing:** 26/11/25
