![System Architecture Framework](../diagrams/Logo_SAF.png)
# Hazard and Risk Analysis Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Operational](../domains.md#Domain-Operational)|[Safety and Security](../aspects.md#Aspect-security--safety)|![Under Construction](../diagrams/Under_construction_icon-yellow.svg )[under construction](../using-saf/maturity.md#under-construction)|
## Example
![HARA](../diagrams/SFV07b_HazardRiskAnalysis.svg)
## Purpose
The System's Hazard and Risk Analysis evaluates identified Hazards and Risks according to safety integrity levels based on the exposure of the operational situation, the controllability of the accident scenario and the severity of the accident scenarios effect.
## Applicability
In general the Hazard and Risk Analysis Viewpoint enables a model-based "System Safety Engineering" as Speciality Engineering Activity of the INCOSE SYSTEM ENGINEERING HANDBOOK 2015 [$ 4.1].
In particular it contributes to safety analyses for the system of interest.
## Stakeholder
* [Safety Expert](../stakeholders.md#safety-expert)
## Concern
* Which criticality has the identified Hazard?
* Are potential mitigations to be considered? 
## Presentation
A bdd illustrates the specific hazard which contains the operational situational, the the accident scenario and the scenario effect.
For an overview a tabular summary is recommended.
## Profile Model Reference
* Situation [RAAML Profile]
* IDCarrier [RAAML Profile]
* PartProperty [SysML Profile]
## Input from other Viewpoints
### Required Viewpoints
* SFV07a Hazard Identification Viewpoint
### Recommended Viewpoints
*none*
