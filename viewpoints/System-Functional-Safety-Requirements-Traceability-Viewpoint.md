![System Architecture Framework](../diagrams/Logo_SAF.png)
# System Safety Requirements Traceability Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Common](../domains.md#Domain-Common)|[Security & Safety](../aspects.md#Aspect-Security--Safety)|![Proposed](../diagrams/Under_construction_icon-red.svg)[proposed](../using-saf/maturity.md#proposed)|
## Example
![SafetyFunction](../diagrams/SFV07c_SafetyFunctionDerivation.svg)
## Purpose
The (functional) Safety Requirements Traceability Viewpoint summarizes the tracebility from a System Function - Malfunctioning Behavior - Safety Goal - Functional Safety Requirement
## Applicability
The Safety Requirements Viewpoint enables a model-based "System Safety Engineering" as Speciality Engineering Activity of the INCOSE SYSTEM ENGINEERING HANDBOOK 2015 [$ 4.1].
## Stakeholder
* [Safety Expert](../stakeholders.md#safety-expert)
* [Regulation Authority](../stakeholders.md#Regulation-Authority)
## Concern
* Which Hazards has to be considered for a System Function?
* Which Safety Goal applies for each Hazard?
* Which Functional Safety Requirements have to be considered to secure a System Function according to the defined Safety Goal?
## Presentation
tbd
## Profile Model Reference
* [SAF_SystemFunction](../stereotypes.md#SAF_SystemFunction)
* MalfunctioningBehavior [RAAML Profile]
* Situation [RAAML Profile]
* IDCarrier [RAAML Profile]
* SafetyGoal [RAAML Profile]
* FunctionalSafetyRequirement [RAAML Profile] 
## Input from other Viewpoints
### Required Viewpoints
*none*
### Recommended Viewpoints
*none*

