![System Architecture Framework](../diagrams/Logo_SAF.png)
# Safety Library Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Common](../domains.md#Domain-Common)|[Security & Safety](../aspects.md#Aspect-Security--Safety)|![Proposed](../diagrams/Under_construction_icon-red.svg)[proposed](../using-saf/maturity.md#proposed)|
## Example
![Exemplary Safety Libraries](../diagrams/SCV07a_SafetyLibraries.svg)
## Purpose
The Safety Library Viewpoint
* enables the usage of safety model libraries in the system model
* documents all used (external) model libraries which are applied in the model in order to analyse and document aspects of system safety
* documents the reason why the safety model library is used to address the norm / standard.  
## Applicability
The Safety Library Viewpoint enables a model-based "System Safety Engineering" as Speciality Engineering Activity of the INCOSE SYSTEM ENGINEERING HANDBOOK 2015 [$ 4.1].
## Stakeholder
* [Safety Expert](../stakeholders.md#safety-expert)
* [Regulation Authority](../stakeholders.md#Regulation-Authority)
## Concern
* Which safety relevant norm, standard and regulation do apply to the SoI?
* Which available safety model libraries (as safety toolbox of applicable norm and standard) apply to the system model?
* What is the reason to use the safety model library?
## Presentation
A package diagram depicts the used model libraries with each having an assigned rational which explain the applicability and usage in the system model.
## Profile Model Reference
* ModelLibrary [SysML Profile]
* Rational [SysML Profile]
* Allocate [SysML Profile]
## Input from other Viewpoints
### Required Viewpoints
* N/A
### Recommended Viewpoints
* N/A
