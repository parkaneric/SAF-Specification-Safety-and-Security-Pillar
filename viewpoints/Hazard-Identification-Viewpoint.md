![System Architecture Framework](../diagrams/Logo_SAF.png)
# Hazard Identification Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Operational](../domains.md#Domain-Operational)|[Safety and Security](../aspects.md#Aspect-security--safety)|![Under Construction](../diagrams/Under_construction_icon-yellow.svg )[under construction](../using-saf/maturity.md#under-construction)|
## Example
![Malfunctioning Behavior](../diagrams/SFV07a_MalfunctioningBehavior.svg)
![Accident Scenario](../diagrams/SFV07a_AccidentScenario.svg)
## Purpose
The Hazard Identification Viewpoint supports in identifying potential hazards caused by the System of Interest based on Operational Situations and/or malfunction behavior.
## Applicability
In general the Hazard Identification Viewpoint enables a model-based "System Safety Engineering" as Speciality Engineering Activity of the INCOSE SYSTEM ENGINEERING HANDBOOK 2015 [$ 4.1].
In particular it contributes to safety analyses for the system of interest. It is recommended to be used when safety is to be analyzed regardless of the specific safety standard to be applied.
## Stakeholder
* [Safety Expert](../stakeholders.md#safety-expert)
## Concern
* Which Operational Situations or malfunction behavior caused potential hazards of the System of Interest?
## Presentation
A bdd reveals the hazards based on Operational Situations or malfunction behavior.
## Profile Model Reference
* [SAF_SystemFunction](../stereotypes.md#SAF_SystemFunction)
* OperationalSituation [RAAML Profile]
* MalfunctioningBehavior [RAAML Profile]
## Input from other Viewpoints
### Required Viewpoints
* SCV07a Safety Library Viewpoint
### Recommended Viewpoints
* SOV07a Operational Situation Viewpoint
* SFV02c_System Functional Breakdown Viewpoint
