![System Architecture Framework](../diagrams/Logo_SAF.png)
# Logical Function Assignment Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Logical](../domains.md#Domain-Logical)|[Mapping & Crossreference](../aspects.md#Aspect-Mapping-&-Crossreference)|![Under Construction](../diagrams/Under_construction_icon-yellow.svg )[under construction](../using-saf/maturity.md#under-construction)|
## Example
![FFDS Context Definition Allocation of Usage](../diagrams/FFDS-Context-Definition-Allocation-of-Usage.svg)
## Purpose
The Logical Function Assignment Viewpoint specifies the assignment of Functions to the Logical SOI Elements.
## Applicability
The Logical Function Allocation Viewpoint supports the "System Architecture Definition process" activities of the INCOSE SYSTEMS ENGINEERING HANDBOOK 2015  .
## Stakeholder
* [Hardware Developer](../stakeholders.md#Hardware-Developer)
* [Software Developer](../stakeholders.md#Software-Developer)
* [System Architect](../stakeholders.md#System-Architect)
## Concern
* Which functions/functional requirements are assigned to a logical item?
## Presentation
A  Logical Function Assignment Matrix featuring
* the call behavior action representing usage of Function(s)
* the part property(s) representing usage of Logical SOI Element(s)
* the allocation relationship between abovementioned elements

## Profile Model Reference
* Allocate [SysML Profile]
* [SAF_FunctionAction](../stereotypes.md#SAF_FunctionAction)
* [SAF_LogicalRole](../stereotypes.md#SAF_LogicalRole)
## Input from other Viewpoints
### Required Viewpoints
* [System Process Viewpoint](System-Process-Viewpoint.md)
* [System Functional Breakdown Viewpoint](System-Functional-Breakdown-Viewpoint.md)
* [Logical Structure Viewpoint](Logical-Structure-Viewpoint.md)
### Recommended Viewpoints
* [System Process Viewpoint](System-Process-Viewpoint.md)