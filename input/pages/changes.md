{: toc}

{: #changes}

This page lists the change history for each version of QI-Core.

### STU8-ballot (8.0.0)

No change requests have been implemented at this time; the primary focus has been on aligning QI-Core profiles with US Core. As part of this alignment, several changes have been inherited from US Core, including:

1. Removal of the US Core Birth Sex Extension from the Patient profile.
1. Deprecation and removal of the US Core Gender Identity Extension from the Patient profile.
1. Redefinition of the US Core Sex Extension, with an updated binding to Federal Administrative Sex.

### STU7 Publication (7.0.1)

#### Corrected Errata in Version 7.0.1 of QI-Core

The changes in this errata to version 7.0.0 of QI-Core have been reviewed by the public through the HL7 errata process. 

The resolution of the community comments has been agreed to and voted on by the members of the HL7 International Clinical Quality work group.

1. The [procedure priority table](qdm-to-qicore.html#procedure-priority) in the qdm-to-qicore page has been corrected.


### STU7 Publication (7.0.0)

1. Added reasonCode and doNotPerform to DeviceRequest negation examples ([FHIR-46669](https://jira.hl7.org/browse/FHIR-46669)) Applied ([here](DeviceRequest-negation-example.html)) and ([here](DeviceRequest-negation-with-code-example.html))  
1. QDM-to-QICore Mapping change Average Blood Pressure to PhysicalExam rather than AssessmentPerformed ([FHIR-46662](https://jira.hl7.org/browse/FHIR-46662)) Applied ([here](qdm-to-qicore.html))
1. Add hyperlink to Using CQL with FHIR IG ([FHIR-47411](https://jira.hl7.org/browse/FHIR-47411)) Applied ([here](modelinfo.html))
1. QI prefix to elements and corrected some extension URLs  ([FHIR-47756](https://jira.hl7.org/browse/FHIR-47756)) Applied ([here](StructureDefinition-qicore-diagnosticreport-lab.html)) and ([here](StructureDefinition-qicore-taskrejected.html)) and ([here](StructureDefinition-qicore-task.html)) and ([here](StructureDefinition-qicore-devicerequest.html)) and ([here](StructureDefinition-qicore-devicerequested.html)) and ([here](StructureDefinition-qicore-careplan.html))
1. 13.12.1 Resource Profile: QICore wording changes  ([FHIR-47540](https://jira.hl7.org/browse/FHIR-47540)) Applied ([here](StructureDefinition-qicore-condition-encounter-diagnosis.html)) 
1. Clarified summary text on index page ([FHIR-47742](https://jira.hl7.org/browse/FHIR-47742)) Applied ([here](index.html))
1. Some Primary Code Path elements are not in the narrative element lists  ([FHIR-47744](https://jira.hl7.org/browse/FHIR-47744)) Applied ([here](StructureDefinition-qicore-careteam.html)) and ([here](StructureDefinition-qicore-familymemberhistory.html))
1. QICore Communication and Communication Not Done primary code path ([FHIR-47747](https://jira.hl7.org/browse/FHIR-47747)) Applied ([here](StructureDefinition-qicore-communication.html) and [here](StructureDefinition-qicore-communicationdone.html) and [here](StructureDefinition-qicore-communicationnotdone.html))
1. Added QI prefix to elements and corrected some extension URLs  ([FHIR-47756](https://jira.hl7.org/browse/FHIR-47756)) Applied ([here](StructureDefinition-qicore-diagnosticreport-lab.html)) and ([here](StructureDefinition-qicore-taskrejected.html)) and ([here](StructureDefinition-qicore-task.html)) and ([here](StructureDefinition-qicore-devicerequest.html)) and ([here](StructureDefinition-qicore-devicerequested.html)) and ([here](StructureDefinition-qicore-careplan.html))
1. Updated NegationReasonCodes in QICore ServiceProhibited ([FHIR-47758](https://jira.hl7.org/browse/FHIR-47758)) Applied ([here](StructureDefinition-qicore-serviceprohibited.html)) and ([here](index.html#terminology-bindings))
1. QI flag not applied consistently for Claim and ClaimResponse profiles ([FHIR-47821](https://jira.hl7.org/browse/FHIR-47821)) Applied ([here](StructureDefinition-qicore-claim.html))
1. QICore Location primary code path  ([FHIR-47880](https://jira.hl7.org/browse/FHIR-47880)) Applied ([here](StructureDefinition-qicore-location.html)) 
1. Updated QDM-QICore mapping page. ([FHIR-48920](https://jira.hl7.org/browse/FHIR-48920), [FHIR-48697](https://jira.hl7.org/browse/FHIR-48697), [FHIR-47404](https://jira.hl7.org/browse/FHIR-47404), [FHIR-45597](https://jira.hl7.org/browse/FHIR-45597)) Applied [here](qdm-to-qicore.html)
1. QICore Location primary code path  ([FHIR-47880](https://jira.hl7.org/browse/FHIR-47880)) Applied ([here](StructureDefinition-qicore-location.html))
1. Updated timing in QICore profiles ([FHIR-48092](https://jira.hl7.org/browse/FHIR-48092)) Applied ([here](StructureDefinition-qicore-immunizationnotdone.html)) and ([here](StructureDefinition-qicore-medicationadministration.html)) and ([here](StructureDefinition-qicore-medicationadministrationnotdone.html)) and ([here](StructureDefinition-qicore-procedurenotdone.html)) and ([here](StructureDefinition-qicore-taskrejected.html))
1. Removed recorded extension from MedicationAdministration and MedicationAdministrationNotDone ([FHIR-48094](https://jira.hl7.org/browse/FHIR-48094)) Applied ([here](StructureDefinition-qicore-medicationadministration.html)) and ([here](StructureDefinition-qicore-medicationadministrationnotdone.html))
1. Updated description for Observation Clinical Result profile. ([FHIR-50209](https://jira.hl7.org/browse/FHIR-50209)) Applied ([here](StructureDefinition-qicore-observation-clinical-result.html))


### STU7-ballot (7.0.0)

1. Should have a CapablityStatement to describe the capabilities of a deployed and configured solution that follows this IG. - 2018-Jan QI-Core #29 ([FHIR-14994](https://jira.hl7.org/browse/FHIR-14994)) Applied ([here](index.html#summary-of-conformance-requirements))
1. It'd be helpful to list a default retriever for each profile ([FHIR-42084](https://jira.hl7.org/browse/FHIR-42084)) Applied in each profile ([here](profiles.html))
1. Consider refactoring to Using CQL IG ([FHIR-43570](https://jira.hl7.org/browse/FHIR-43570)) Applied ([here](modelinfo.html)) and ([here](patterns.html)) and ([here](negation.html))
1. MedicationNotRequested binding is incorrect ([FHIR-44737](https://jira.hl7.org/browse/FHIR-44737)) Applied ([here](https://hl7.org/fhir/us/qicore/STU6/StructureDefinition-qicore-medicationnotrequested.html))
1. MedicationDispenseDeclined negation pattern incorrectly allows for medication reference ([FHIR-44738](https://jira.hl7.org/browse/FHIR-44738)) Applied ([here](StructureDefinition-qicore-medicationdispensedeclined.html))
1. TLS 1.1 has been deprecated ([FHIR-44743](https://jira.hl7.org/browse/FHIR-44743)) Applied ([here](index.html#privacy-security-and-consent))
1. Link to Terminology "guidance section" doesn't work as intended ([FHIR-44808](https://jira.hl7.org/browse/FHIR-44808)) Applied ([here](terminology.html))
1. Add reference to 3 new US Core observation profiles in QI-Core ([FHIR-45359](https://jira.hl7.org/browse/FHIR-45359)) Applied ([here](profiles.html))
1. Update QI-Core references to USCDI consistent with US Core 7.0 approach ([FHIR-45360](https://jira.hl7.org/browse/FHIR-45360)) Applied in each profile ([here](profiles.html))
1. Update qicore-notDoneValueSet Extension ([FHIR-45368](https://jira.hl7.org/browse/FHIR-45368)) Applied ([here](extensions.html))
1. Update QI-Core to use extensions pack ([FHIR-45369](https://jira.hl7.org/browse/FHIR-45369)) Applied ([here](extensions.html))
1. Update AllergyIntolerance, CarePlan, CareTeam, and Coverage profiles to address US Core 7.0 ([FHIR-45395](https://jira.hl7.org/browse/FHIR-45395)) Applied ([here](StructureDefinition-qicore-careplan.html)) and ([here](StructureDefinition-qicore-careteam.html))
1. Update QI-Core Condition Encounter Diagnosis and QI-Core Condition Problems and Health Concerns Profiles to build off of US Core 7.0 ([FHIR-45396](https://jira.hl7.org/browse/FHIR-45396)) Applied ([here](StructureDefinition-qicore-condition-problems-health-concerns.html)) and ([here](StructureDefinition-qicore-condition-encounter-diagnosis.html))
1. Update QICore DiagnosticReport Profile for Laboratory Results Reporting and QI Core DiagnosticReport Profile for Report and Note Exchange to reflect updates in US Core 7.0's respective profile ([FHIR-45397](https://jira.hl7.org/browse/FHIR-45397)) Applied ([here](StructureDefinition-qicore-diagnosticreport-lab.html))
1. Update QICore Encounter profile to build off of US Core 7.0 Encounter profile ([FHIR-45398](https://jira.hl7.org/browse/FHIR-45398)) Applied ([here](StructureDefinition-qicore-encounter.html))
1. Update QI-Core Goal profile to reflect US Core 7.0 Goal profile ([FHIR-45399](https://jira.hl7.org/browse/FHIR-45399)) Applied ([here](StructureDefinition-qicore-goal.html))
1. Update QI-Core Immunization, QI-Core ImmunizationNotDone profiles to build from US 7.0 Core Immunization Profile ([FHIR-45400](https://jira.hl7.org/browse/FHIR-45400)) Applied ([here](StructureDefinition-qicore-immunizationnotdone.html))
1. Update QI-Core Location profile consistently with US Core version 7.0 Location Profile ([FHIR-45401](https://jira.hl7.org/browse/FHIR-45401)) Applied ([here](StructureDefinition-qicore-location.html))
1. Update QI-Core Medication and QI-Core MedicationDispense and QI-Core MedicationDispenseDeclined profiles to build from US Core 7.0 Medication and MedicationDispense profiles ([FHIR-45402](https://jira.hl7.org/browse/FHIR-45402)) Applied ([here](StructureDefinition-qicore-medicationdispense.html)) and ([here](StructureDefinition-qicore-medicationdispensedeclined.html))
1. Update QI-Core MedicationRequest and QI-Core MedicationNotRequested to changes reflected in US Core 7.0 MedicationRequest Profile ([FHIR-45403](https://jira.hl7.org/browse/FHIR-45403)) Applied ([here](StructureDefinition-qicore-medicationrequest.html)) and ([here](https://hl7.org/fhir/us/qicore/STU6/StructureDefinition-qicore-medicationnotrequested.html))
1. Update QI-Core SimpleObservation and ObservationCancelled to reflect changes in US Core 7.0 ([FHIR-45415](https://jira.hl7.org/browse/FHIR-45415)) Applied ([here](StructureDefinition-qicore-simple-observation.html)) and ([here](https://hl7.org/fhir/us/qicore/STU6/StructureDefinition-qicore-observationcancelled.html))
1. Update QI-Core ObservationClinicalResult and QI-Core LaboratoryResultObservation Profile to reflect changes in US Core 7.0 ([FHIR-45416](https://jira.hl7.org/browse/FHIR-45416)) Applied ([here](StructureDefinition-qicore-observation-clinical-result.html)) and ([here](StructureDefinition-qicore-observation-lab.html))
1. Update QI-Core ObservationScreeningAssessment to reflect changes in US Core 7.0 ([FHIR-45417](https://jira.hl7.org/browse/FHIR-45417)) Applied ([here](StructureDefinition-qicore-observation-screening-assessment.html))
1. Update QI-Core Organization Profile to reflect changes in US Core 7.0 ([FHIR-45419](https://jira.hl7.org/browse/FHIR-45419)) Applied ([here](StructureDefinition-qicore-organization.html))
1. Update QI-Core Patient profile to align with changes in US Core 7.0 ([FHIR-45424](https://jira.hl7.org/browse/FHIR-45424)) Applied ([here](StructureDefinition-qicore-patient.html))
1. Update QI-Core Practitioner profile to reflect changes in US Core 7.0 ([FHIR-45425](https://jira.hl7.org/browse/FHIR-45425)) Applied ([here](StructureDefinition-qicore-practitioner.html))
1. Update QI-Core PractitionerRole profile to reflect changes in US Core 7.0 ([FHIR-45426](https://jira.hl7.org/browse/FHIR-45426)) Applied ([here](StructureDefinition-qicore-practitionerrole.html))
1. Update QI-Core Related Person to reflect changes in US Core 7.0 ([FHIR-45427](https://jira.hl7.org/browse/FHIR-45427)) Applied ([here](StructureDefinition-qicore-relatedperson.html))
1. Update QI-Core Procedure and ProcedureNotDone to reference US Core 7.0 respective profile ([FHIR-45429](https://jira.hl7.org/browse/FHIR-45429)) Applied ([here](StructureDefinition-qicore-procedure.html)) and ([here](StructureDefinition-qicore-procedurenotdone.html))
1. Update QI-Core QuestionnaireResponse profile to align with updated US Core 7.0 respective profile ([FHIR-45430](https://jira.hl7.org/browse/FHIR-45430)) Applied ([here](StructureDefinition-qicore-questionnaireresponse.html))
1. Update QI-Core ServiceRequest and QI-Core ServiceNotRequested to align with changes to US Core 7.0 respective profiles ([FHIR-45431](https://jira.hl7.org/browse/FHIR-45431)) Applied ([here](https://hl7.org/fhir/us/qicore/STU6/StructureDefinition-qicore-servicenotrequested.html)) and ([here](https://hl7.org/fhir/us/qicore/STU6/StructureDefinition-qicore-servicerequest.html))
1. Update QDM to QI-Core Mapping Tables to reference changes in QI-Core 7.0 ([FHIR-45597](https://jira.hl7.org/browse/FHIR-45597)) Applied ([here](qdm-to-qicore.html))
1. Limit subject reference in AdverseEvent to patient ([FHIR-45693](https://jira.hl7.org/browse/FHIR-45693)) Applied ([here](StructureDefinition-qicore-adverseevent.html))
1. Update Negation page to include 3 new US Core observation profiles ([FHIR-45722](https://jira.hl7.org/browse/FHIR-45722)) Applied ([here](negation.html))
1. Update landing page for version 7.0 ([FHIR-45947](https://jira.hl7.org/browse/FHIR-45947)) Applied ([here](index.html))
1. Move Negation Value Set to THO ([FHIR-45957](https://jira.hl7.org/browse/FHIR-45957)) Applied ([here](ValueSet-qicore-negation-reason.html))
1. Update QI-Core Claim to include key elements for present on admission and principal diagnosis ([FHIR-45959](https://jira.hl7.org/browse/FHIR-45959)) Applied ([here](StructureDefinition-qicore-claim.html))
1. Add (QI) tags to QI-Core profile elements used in test FHIR measures ([FHIR-46015](https://jira.hl7.org/browse/FHIR-46015)) Applied in each profile ([here](profiles.html))
1. Add list of QI-Core-flagged elements to the narrative ([FHIR-46030](https://jira.hl7.org/browse/FHIR-46030)) Applied in each profile ([here](profiles.html))
1. QICore MedicationRequest prohibits reportedBoolean ([FHIR-46040](https://jira.hl7.org/browse/FHIR-46040)) Applied ([here](StructureDefinition-qicore-medicationrequest.html))
1. Update medication[x] content across not done for reason medication actions to assure consistency ([FHIR-46291](https://jira.hl7.org/browse/FHIR-46291)) Applied ([here](https://hl7.org/fhir/us/qicore/STU6/StructureDefinition-qicore-medicationnotrequested.html)) and ([here](StructureDefinition-qicore-medicationadministrationnotdone.html)) and ([here](StructureDefinition-qicore-medicationdispensedeclined.html))
1. QICoreCommunicationRequest description text change ([FHIR-46654](https://jira.hl7.org/browse/FHIR-46654)) Applied ([here](StructureDefinition-qicore-task.html))
1. Remove "ADDITIONAL USCDI" indicator ([FHIR-46657](https://jira.hl7.org/browse/FHIR-46657)) Applied ([here](https://hl7.org/fhir/us/qicore/STU6/StructureDefinition-qicore-medicationnotrequested.html)) and ([here](StructureDefinition-qicore-medicationrequest.html))
1. QICoreTask description text change ([FHIR-46659](https://jira.hl7.org/browse/FHIR-46659)) Applied ([here](StructureDefinition-qicore-task.html))
1. Update to QI Core Profile Headings w/Current Version ([FHIR-47398](https://jira.hl7.org/browse/FHIR-47398)) Applied ([here](profiles.html))
1. Correct duplicate content error from MustSupport Flag section ([FHIR-47407](https://jira.hl7.org/browse/FHIR-47407)) Applied ([here](index.html#mustsupport-flag))
1. Removed performer items, added reasonCode to procedure negation examples ([FHIR-46670](https://jira.hl7.org/browse/FHIR-46670)) Applied ([here](Procedure-negation-with-code-example.html)) and ([here](Procedure-negation-example.html))
1. Add (QI) flag and qicode keyelement extension([FHIR-47746](https://jira.hl7.org/browse/FHIR-47746)) Applied to multiple places
1. Add (QI) Key Element extensions ([FHIR-47860](https://jira.hl7.org/browse/FHIR-47860)) Applied multiple places

### STU6 Release (6.0.0)

1. QICore Simple Observation Profile - removed additional subjects ([FHIR-41755](https://jira.hl7.org/browse/FHIR-41755))
1. QI-Core is spelled various ways throughout the implementation guide ([FHIR-41783](https://jira.hl7.org/browse/FHIR-41783))
1. Technical correction: remove "`" at the end of the sentence. ([FHIR-41784](https://jira.hl7.org/browse/FHIR-41784))
1. The first sentence of bullet point 1 in 1.0.1 must be updated ([FHIR-41786](https://jira.hl7.org/browse/FHIR-41786))
1. Add a space between "support" and "(vMR)"([FHIR-41787](https://jira.hl7.org/browse/FHIR-41787))
1. Remove comma after "data" ([FHIR-41788](https://jira.hl7.org/browse/FHIR-41788))
1. Consider capitalizing "url" to "URL" throughout the entire implementation guide. ([FHIR-41789](https://jira.hl7.org/browse/FHIR-41789))
1. Are any of these duplicates in the table in 8.7? ([FHIR-41790](https://jira.hl7.org/browse/FHIR-41790))
1. 1.4 Relevance of QI-Core Profiles to Authors ([FHIR-41974](https://jira.hl7.org/browse/FHIR-41974))
1. 1.5 Scope ([FHIR-41975](https://jira.hl7.org/browse/FHIR-41975))
1. 1.5 Scope ([FHIR-41976](https://jira.hl7.org/browse/FHIR-41976))
1. 1.5 Scope ([FHIR-41978](https://jira.hl7.org/browse/FHIR-41978))
1. 1.6 Privacy, Security, and Consent ([FHIR-41979](https://jira.hl7.org/browse/FHIR-41979))
1. 1.6 Privacy, Security, and Consent ([FHIR-41980](https://jira.hl7.org/browse/FHIR-41980))
1. 1.6 Privacy, Security, and Consent ([FHIR-41981](https://jira.hl7.org/browse/FHIR-41981))
1. 1.7 Provenance ([FHIR-41982](https://jira.hl7.org/browse/FHIR-41982))
1. 1.8 Relationship to Other Initiatives ([FHIR-41983](https://jira.hl7.org/browse/FHIR-41983))
1. 1.8 Relationship to Other Initiatives ([FHIR-41984](https://jira.hl7.org/browse/FHIR-41984))
1. 1.11 MustSupport Flag ([FHIR-41987](https://jira.hl7.org/browse/FHIR-41987))
1. 1.11 MustSupport Flag ([FHIR-41988](https://jira.hl7.org/browse/FHIR-41988))
1. 1.11 MustSupport Flag ([FHIR-41989](https://jira.hl7.org/browse/FHIR-41989))
1. 1.11 MustSupport Flag ([FHIR-41991](https://jira.hl7.org/browse/FHIR-41991))
1. 1.13.3 Negation Rationale ([FHIR-41994](https://jira.hl7.org/browse/FHIR-41994))
1. 1.13.3 Negation Rationale ([FHIR-41995](https://jira.hl7.org/browse/FHIR-41995))
1. 1.13.4 Guidance for the use of Negation Profiles ([FHIR-41996](https://jira.hl7.org/browse/FHIR-41996))
1. Value Sets ([FHIR-41997](https://jira.hl7.org/browse/FHIR-41997))
1. 1.13.4 Guidance for the use of Negation Profiles ([FHIR-41999](https://jira.hl7.org/browse/FHIR-41999))
1. 1.13.4 Guidance for the use of Negation Profiles ([FHIR-42000](https://jira.hl7.org/browse/FHIR-42000))
1. 1.13.4 Guidance for the use of Negation Profiles ([FHIR-42001](https://jira.hl7.org/browse/FHIR-42001))
1. 1.13.4 Guidance for the use of Negation Profiles ([FHIR-42002](https://jira.hl7.org/browse/FHIR-42002))
1. NutritionIntake profile should more closely address the FHIR R5 NutritionIntake modeling ([FHIR-42009](https://jira.hl7.org/browse/FHIR-42009))
1. onAdmission required value set shoud use QICore Present On Admission Codes ([FHIR-42054](https://jira.hl7.org/browse/FHIR-42054))
1. Pregnancy Status Profile Needs More Detail ([FHIR-42056](https://jira.hl7.org/browse/FHIR-42056))
1. Typo in Blood Pressure Profile ([FHIR-42057](https://jira.hl7.org/browse/FHIR-42057))
1. Typo in Encounter-Related Diagnoses and Procedures ([FHIR-42058](https://jira.hl7.org/browse/FHIR-42058))
1. Provide Additional Guidance on Negation Profiles ([FHIR-42099](https://jira.hl7.org/browse/FHIR-42099))
1. Remove Resource Rows from Profile Table ([FHIR-42100](https://jira.hl7.org/browse/FHIR-42100))
1. Profile Table Typo: DiagnositcReport ([FHIR-42101](https://jira.hl7.org/browse/FHIR-42101))
1. Links to lines of code on GitHub should be targeted to a commit or release ([FHIR-42153](https://jira.hl7.org/browse/FHIR-42153))
1. Multiple issues with specification of QICore Nutrition Intake profile ([FHIR-42158](https://jira.hl7.org/browse/FHIR-42158))
1. Typos found in Quality Data Model (QDM)v5.6 to QI-Core R6 Mapping ([FHIR-42370](https://jira.hl7.org/browse/FHIR-42370))
1. Typo in 8.8 IP Statement ([FHIR-42371](https://jira.hl7.org/browse/FHIR-42371))
1. Bad URL link in 5 QI-Core Extensions ([FHIR-42372](https://jira.hl7.org/browse/FHIR-42372))
1. Typos in 9.12.3 Encounter-Related Diagnoses and Procedures ([FHIR-42375](https://jira.hl7.org/browse/FHIR-42375))
1. Bolding of "SHALLs" ([FHIR-42406](https://jira.hl7.org/browse/FHIR-42406))
1. Add space between "patient" and "It" ([FHIR-42407](https://jira.hl7.org/browse/FHIR-42407))
1. US Core is spelled "US Core" and "USCore" throughout the implementation guide. ([FHIR-42408](https://jira.hl7.org/browse/FHIR-42408))
1. Change "inherit" to "inherited" in the first sentence of 2.2. ([FHIR-42409](https://jira.hl7.org/browse/FHIR-42409))
1. Broken Links or Sign In Required ([FHIR-42411](https://jira.hl7.org/browse/FHIR-42411))
1. Definition of "QICore Reasons Rejecting Goal" in 6.1 ([FHIR-42412](https://jira.hl7.org/browse/FHIR-42412))
1. Add space between "i.e.," and "no" in last row of table in 9.4 ([FHIR-42415](https://jira.hl7.org/browse/FHIR-42415))
1. Either parenthesis is included in error after the word "individual/organization" or the other half is missing in last row of 9.5.3. ([FHIR-42416](https://jira.hl7.org/browse/FHIR-42416))
1. Remove double space between "etc." and "The following" in the first paragraph of 9.8. ([FHIR-42417](https://jira.hl7.org/browse/FHIR-42417))
1. Regarding the sentence, "Mere disclosure of information would be considered a Communication."...would this be an Encounter, if it's patient to practitioner? ([FHIR-42421](https://jira.hl7.org/browse/FHIR-42421))
1. Remove sentence in 9.9 ([FHIR-42422](https://jira.hl7.org/browse/FHIR-42422))
1. Remove double space between "Immunization, Administered." and "The Immunization profile". ([FHIR-42426](https://jira.hl7.org/browse/FHIR-42426))
1. the comma after "record" should be a period ([FHIR-42427](https://jira.hl7.org/browse/FHIR-42427))
1. "In" should be lowercase ([FHIR-42429](https://jira.hl7.org/browse/FHIR-42429))
1. Should skilled nursing facilities, CBRFs, outpatient surgery centers, etc. be included in the list? ([FHIR-42432](https://jira.hl7.org/browse/FHIR-42432))
1. Remove extra space between "necessary" and "The" ([FHIR-42433](https://jira.hl7.org/browse/FHIR-42433))
1. Change "self-prescribed" to "self-reported" throughout 9.18.3. ([FHIR-42434](https://jira.hl7.org/browse/FHIR-42434))
1. Expand list of examples ([FHIR-42437](https://jira.hl7.org/browse/FHIR-42437))
1. Remove extra space between sentences in 9.21.2.  ([FHIR-42438](https://jira.hl7.org/browse/FHIR-42438))
1. Change "existing" to "exist" ([FHIR-42439](https://jira.hl7.org/browse/FHIR-42439))
1. Add "(AE)" to the sentence ([FHIR-42440](https://jira.hl7.org/browse/FHIR-42440))
1. Change "assesment" to "assessment" in two places in 11.0.5: ([FHIR-42442](https://jira.hl7.org/browse/FHIR-42442))
1. Change "individuals" to "individual's" in two places in 11.0.5: ([FHIR-42444](https://jira.hl7.org/browse/FHIR-42444))
1. Is it supposed to be "valueset" instead of "valuset"? ([FHIR-42445](https://jira.hl7.org/browse/FHIR-42445))
1. Change "Inhalent" to "Inhalant" ([FHIR-42446](https://jira.hl7.org/browse/FHIR-42446))
1. Change "appropiateness" to "appropriateness" in two places in 11.0.5 ([FHIR-42667](https://jira.hl7.org/browse/FHIR-42667))
1. Develop QI-Core profile based on ODH ([FHIR-42448](https://jira.hl7.org/browse/FHIR-42448))
1. Remove QI-Core specific Must Support flags ([FHIR-42889](https://jira.hl7.org/browse/FHIR-42889))
1. Cut-and-paste errors in QDM to QI-Core mapping table ([FHIR-42993](https://jira.hl7.org/browse/FHIR-42993))
1. QDM to QI-Core Mapping section 9.22.1 - Modify based on FHIR-42158 resolution ([FHIR-42987](https://jira.hl7.org/browse/FHIR-42987))
1. Relax cardinality for specific elements to stay with US Core cardinality assignments ([FHIR-43010](https://jira.hl7.org/browse/FHIR-43010))
1. Correct QDM Substance mapping to Observation ([FHIR-44605](https://jira.hl7.org/browse/FHIR-44605))
1. Correct mapping for prinicpal procedure ([FHIR-44835](https://jira.hl7.org/browse/FHIR-44835))




### STU6-ballot (6.0.0)

1. History page is broken/absent ([FHIR-37970](https://jira.hl7.org/browse/FHIR-37970))
1. Provide guidance re: convention for differentiating admission from arrival time ([FHIR-40547](https://jira.hl7.org/browse/FHIR-40547))
1. Remove Must Supports and Adverse Event Profile ([FHIR-41263](https://jira.hl7.org/browse/FHIR-41263))
1. remove Must Support for Encounter.diagnosis and its respective elements ([FHIR-41265](https://jira.hl7.org/browse/FHIR-41265))
1. Round out ODH example ([FHIR-41286](https://jira.hl7.org/browse/FHIR-41286))
1. Reference ODH in Profiles and Extensions ([FHIR-41287](https://jira.hl7.org/browse/FHIR-41287))
1. Create extension profile for NutritionIntake ([FHIR-41338](https://jira.hl7.org/browse/FHIR-41338))
1. Adjust QI-Core AllergyIntolerance Must Supports ([FHIR-41461](https://jira.hl7.org/browse/FHIR-41461))
1. Adjust QI-Core Communication must supports ([FHIR-41462](https://jira.hl7.org/browse/FHIR-41462))
1. Adjust QI-Core CommunicationNotDone must supports ([FHIR-41463](https://jira.hl7.org/browse/FHIR-41463))
1. Adjust QI-Core Condition Problems Health Concerns must supports ([FHIR-41464](https://jira.hl7.org/browse/FHIR-41464))
1. Adjust QI-Core Coverage must supports ([FHIR-41465](https://jira.hl7.org/browse/FHIR-41465))
1. Adjust QI-Core Device Not Requested must supports ([FHIR-41466](https://jira.hl7.org/browse/FHIR-41466))
1. Adjust QI-Core Device Request must supports ([FHIR-41467](https://jira.hl7.org/browse/FHIR-41467))
1. Adjust QI-Core Immunization must supports  ([FHIR-41468](https://jira.hl7.org/browse/FHIR-41468))
1. Adjust QI-Core Laboratory Result Observation must supports ([FHIR-41469](https://jira.hl7.org/browse/FHIR-41469))
1. Adjust QI-Core Medication Not Requested must supports  ([FHIR-41470](https://jira.hl7.org/browse/FHIR-41470))
1. Adjust QI-Core Medication Administration must supports ([FHIR-41471](https://jira.hl7.org/browse/FHIR-41471))
1. Adjust QI-Core Medication Administration Not Done must supports ([FHIR-41472](https://jira.hl7.org/browse/FHIR-41472))
1. Adjust QI-Core Medication Dispense must supports ([FHIR-41473](https://jira.hl7.org/browse/FHIR-41473))
1. Adjust QI-Core Medication Request must supports ([FHIR-41474](https://jira.hl7.org/browse/FHIR-41474))
1. Adjust QI-Core Observation must supports ([FHIR-41475](https://jira.hl7.org/browse/FHIR-41475))
1. Adjust QI-Core Observation Cancelled must supports ([FHIR-41476](https://jira.hl7.org/browse/FHIR-41476))
1. Adjust QI-Core Observation Clinical Test Result must supports ([FHIR-41477](https://jira.hl7.org/browse/FHIR-41477))
1. Adjust QI-Core Patient must supports ([FHIR-41479](https://jira.hl7.org/browse/FHIR-41479))
1. Adjust QI-Core Procedure must supports ([FHIR-41480](https://jira.hl7.org/browse/FHIR-41480))
1. Adjust QI-Core Procedure Not Done must supports ([FHIR-41481](https://jira.hl7.org/browse/FHIR-41481))
1. Adjust QI-Core Service Not Requested must supports ([FHIR-41482](https://jira.hl7.org/browse/FHIR-41482))
1. Adjust QI-Core ServiceRequest must supports ([FHIR-41483](https://jira.hl7.org/browse/FHIR-41483))
1. Add MS elements to QI-Core Claim profile ([FHIR-41505](https://jira.hl7.org/browse/FHIR-41505))
1. Update QI-Core Medication Dispense Declined to align with US Core and USCDI ([FHIR-41511](https://jira.hl7.org/browse/FHIR-41511))
1. Remove Observation Imaging from QI-Core 6.0 (merged with Clinical Result in US Core 6.1.0 ([FHIR-41525](https://jira.hl7.org/browse/FHIR-41525))
1. Update QI-Core Observation Survey to US Core 6.1.0 Observation Screening Assessment ([FHIR-41526](https://jira.hl7.org/browse/FHIR-41526))
1. Update QICore ConditionEncounterDiagnosis to US Core ConditionEncounterDiagnosis and remove extraneous elements ([FHIR-41527](https://jira.hl7.org/browse/FHIR-41527))
1. QI Core Version 6.0 ImmunizationNotDone Update recommendations ([FHIR-41528](https://jira.hl7.org/browse/FHIR-41528))
1. Remove QI-Core Specimen profile and inherit new US Core Specimen profile ([FHIR-41530](https://jira.hl7.org/browse/FHIR-41530))
1. Update QI-Core CarePlan Profile consistent with US Core 6.1.0 ([FHIR-41533](https://jira.hl7.org/browse/FHIR-41533))
1. Update QI-Core CareTeam to align with US Core 6.1.0 and simplify ([FHIR-41534](https://jira.hl7.org/browse/FHIR-41534))
1. Update QI-Core DiagnosticReportLab to align with US Core 6.1.0 ([FHIR-41535](https://jira.hl7.org/browse/FHIR-41535))
1. Update QI-Core DiagnosticProfileforReportandNoteExchange ([FHIR-41536](https://jira.hl7.org/browse/FHIR-41536))
1. Update QI-Core Goal profile to align with US Core 6.1.0 and to simplify ([FHIR-41537](https://jira.hl7.org/browse/FHIR-41537))
1. Update QI-Core to align with US Core Location profile ([FHIR-41538](https://jira.hl7.org/browse/FHIR-41538))
1. Update QI-Core Medication profile to align with US Core 6.1.0 ([FHIR-41539](https://jira.hl7.org/browse/FHIR-41539))
1. Update QI-Core Organization Profile to align with US Core 6.1.0 ([FHIR-41540](https://jira.hl7.org/browse/FHIR-41540))
1. Update QI-Core Practitioner profile to align with US Core 6.1.0  ([FHIR-41541](https://jira.hl7.org/browse/FHIR-41541))
1. Update QI-Core PractitionerRole profile to align with US Core 6.1.0 ([FHIR-41542](https://jira.hl7.org/browse/FHIR-41542))
1. Update QI-Core QuestionnaireResponse profile to align with US Core 6.1.0 ([FHIR-41543](https://jira.hl7.org/browse/FHIR-41543))
1. Update QI-Core RelatedPerson profile to align with US Core 6.1.0 ([FHIR-41544](https://jira.hl7.org/browse/FHIR-41544))
1. Include Question to Balloters in QI-Core September Ballot ([FHIR-41545](https://jira.hl7.org/browse/FHIR-41545))
1. Typo in 11.79.1 AllergyIntolerance Example headers ([FHIR-41555](https://jira.hl7.org/browse/FHIR-41555))
1. Update QI-Core QDM to QI-Core mapping section for QI-Core 6.0 ([FHIR-41570](https://jira.hl7.org/browse/FHIR-41570))
1. Add additional notes to commenters in QI-Core 6.0 ballot ([FHIR-41574](https://jira.hl7.org/browse/FHIR-41574))
1. Update landing page for QI-Core 6.0 ballot ([FHIR-41575](https://jira.hl7.org/browse/FHIR-41575))
1. Removed NutritionIntake profile and example. Removed related Example-Foods valueset ([FHIR-41258](https://jira.hl7.org/browse/FHIR-41258), [FHIR-42009](https://jira.hl7.org/browse/FHIR-42009))
1. Altered profiles table in profiles.md to increase readability. ([FHIR-42100](https://jira.hl7.org/browse/FHIR-42100))
1. Changed "self-prescribed" to "self-reported" throughout section 9.18.3 in QDM-QICore Mapping ([FHIR-42434](https://jira.hl7.org/browse/FHIR-42434))
1. Added further details to Race, Ethnicity and Sex table elements in QDM-QICore Mapping for Patient Characteristics table ([FHIR-41932](https://jira.hl7.org/browse/FHIR-41932))
1. Clarifying text edits in QDM-QI Core mapping ([FHIR-42432](https://jira.hl7.org/browse/FHIR-42432), [FHIR-42429](https://jira.hl7.org/browse/FHIR-42429), [FHIR-42422](https://jira.hl7.org/browse/FHIR-42422), [FHIR-42421](https://jira.hl7.org/browse/FHIR-42421) )


### STU5 Release (5.0.0)

1. Add ODH - 2016-09 qicore #21 ([FHIR-12091](https://jira.hl7.org/browse/FHIR-12091))
1. Add ODH - 2018-Jan QI-Core #33 ([FHIR-14998](https://jira.hl7.org/browse/FHIR-14998))
1. Update QI-Core to incorporate changes from US Core 3.2.0 ballot ([FHIR-30116](https://jira.hl7.org/browse/FHIR-30116))
1. qicore-encounter-diagnosisPresentOnAdmission not applicable for outpatient encounters but always required when sending a diagnosis ([FHIR-31764](https://jira.hl7.org/browse/FHIR-31764))
1. Update Cumulative Medication Duration examples in upcoming update ([FHIR-32007](https://jira.hl7.org/browse/FHIR-32007))
1. Add extension for MedicationDispense.statusChange ([FHIR-32805](https://jira.hl7.org/browse/FHIR-32805))
1. Add pattern for blood pressure ([FHIR-32945](https://jira.hl7.org/browse/FHIR-32945))
1. QI Core Specimen Profile not used in QI Core ImagingStudy or QI Core ServiceRequest ([FHIR-32967](https://jira.hl7.org/browse/FHIR-32967))
1. QI Core ImagingStudy needs more Resource types for Referrer and Interpreter ([FHIR-32968](https://jira.hl7.org/browse/FHIR-32968))
1. Mark timing.bounds as mustSupport ([FHIR-33017](https://jira.hl7.org/browse/FHIR-33017))
1. Mark mandatory top level elements MUST SUPPORT ([FHIR-33029](https://jira.hl7.org/browse/FHIR-33029))
1. QI Core Immunization Profile should only allow Completed status and statusReason should not be allowed ([FHIR-33087](https://jira.hl7.org/browse/FHIR-33087))
1. Remove duplicate profile statements ([FHIR-33199](https://jira.hl7.org/browse/FHIR-33199))
1. FamilyMemberHistory profile needs to have a more constrained binding on Relationship code set ([FHIR-33230](https://jira.hl7.org/browse/FHIR-33230))
1. Need ClaimResponse Resource added to QI Core Profiles ([FHIR-33373](https://jira.hl7.org/browse/FHIR-33373))
1. Should Encounter.diagnosis.condition be restricted to reference (condition) and NOT (procedure) and specify the change in QDM mapping - September Update ([FHIR-33491](https://jira.hl7.org/browse/FHIR-33491))
1. Medication.code Preferred binding is less than US Core extensible binding ([FHIR-34071](https://jira.hl7.org/browse/FHIR-34071))
1. Medication.form appears on the Differential View but no apparent change from US Core ([FHIR-34072](https://jira.hl7.org/browse/FHIR-34072))
1. Aligning with US Core - New conformance expectations page ([FHIR-34154](https://jira.hl7.org/browse/FHIR-34154))
1. Align with US CORE on VSAC terminology references ([FHIR-34167](https://jira.hl7.org/browse/FHIR-34167))
1. Change $docref start and end input parameter types from date to dateTime ([FHIR-34169](https://jira.hl7.org/browse/FHIR-34169))
1. Align with US Core 4.0 - must support complex elements ([FHIR-34176](https://jira.hl7.org/browse/FHIR-34176))
1. Align with US Core 4.0 - include VSAC instructions in terminology section ([FHIR-34177](https://jira.hl7.org/browse/FHIR-34177))
1. Align with US Core 4.0 - must support choice of profile elements ([FHIR-34178](https://jira.hl7.org/browse/FHIR-34178))
1. Align with US Core 4.0 - align invariants and binding change in PractitionerRole ([FHIR-34179](https://jira.hl7.org/browse/FHIR-34179))
1. CommunicationNotDone profile does not have Subject as Must Support ([FHIR-34313](https://jira.hl7.org/browse/FHIR-34313))
1. AdverseEvent. referenceDocument does not reference US Core Document Reference ([FHIR-34367](https://jira.hl7.org/browse/FHIR-34367))
1. AdverseEvent.contributor does not reference QI Core profiles for  Contributor or suspectEntity.causality.author ([FHIR-34368](https://jira.hl7.org/browse/FHIR-34368))
1. Organization profile should mirror US Core telecom must support elements of system and value ([FHIR-34482](https://jira.hl7.org/browse/FHIR-34482))
1. Add due duration to QI Core Goal.target ([FHIR-34484](https://jira.hl7.org/browse/FHIR-34484))
1. Consider updating StructureDefinition-qicore-diagnosticreport-lab to mirror US Core for performer element ([FHIR-34531](https://jira.hl7.org/browse/FHIR-34531))
1. Consider updating choice type for Encounter.referenceReason to mirror US Core ([FHIR-34534](https://jira.hl7.org/browse/FHIR-34534))
1. Careplan.text.div should be MS to mirror US Core ([FHIR-34535](https://jira.hl7.org/browse/FHIR-34535))
1. Consider adding MS datatypes on observation.value[x] ([FHIR-34536](https://jira.hl7.org/browse/FHIR-34536))
1. Consider adding MS datatypes on observation.effective[x] ([FHIR-34537](https://jira.hl7.org/browse/FHIR-34537))
1. Update definition of diagnosticreport.effective[x] ([FHIR-34557](https://jira.hl7.org/browse/FHIR-34557))
1. Consider adding MS on medicationrequest.requester choice type of Practitioner ([FHIR-34559](https://jira.hl7.org/browse/FHIR-34559))
1. ServiceRequest.statusReason is not bound to a value set yet it is an extension added for use by QI Core ([FHIR-35100](https://jira.hl7.org/browse/FHIR-35100))
1. Change example value sets for MS items to Preferred - Immunization-related ([FHIR-35813](https://jira.hl7.org/browse/FHIR-35813))
1. Change example value sets for MS items to Preferred - Medication-related ([FHIR-35814](https://jira.hl7.org/browse/FHIR-35814))
1. Change QI Core Communication Resource MS items to Preferred Value Set bindings ([FHIR-35815](https://jira.hl7.org/browse/FHIR-35815))
1. QI Core Care Plan and Goal Profiles have MS items with example bindings to value sets - change to Preferred ([FHIR-35816](https://jira.hl7.org/browse/FHIR-35816))
1. Change value set bindings for QI-Core AllergyIntolerance, AdverseEvent, Condition, Procedure elements with MS ([FHIR-35817](https://jira.hl7.org/browse/FHIR-35817))
1. QICore Flag profile elements with MS example bindings should change to preferred bindings ([FHIR-35818](https://jira.hl7.org/browse/FHIR-35818))
1. QICore ServiceRequest, ServiceNotRequested MS item should have preferred value set bindings ([FHIR-35819](https://jira.hl7.org/browse/FHIR-35819))
1. Change QICore Specimen value set bindings where items are Must Support ([FHIR-35820](https://jira.hl7.org/browse/FHIR-35820))
1. Device-related QI-Core profile elements that are Must Support should have preferred bindings, not example bindings ([FHIR-35821](https://jira.hl7.org/browse/FHIR-35821))
1. QI-Core observation-related profile Must Support elements should all have Preferred bindings, not example bindings ([FHIR-35822](https://jira.hl7.org/browse/FHIR-35822))
1. QI-Core Task profile elements that are Must Support should use preferred bindings to value sets, not examples ([FHIR-35823](https://jira.hl7.org/browse/FHIR-35823))
1. QI-Core Encounter and Organization Profile MS elements should have preferred value set bindings, not examples ([FHIR-35824](https://jira.hl7.org/browse/FHIR-35824))
1. QI Core Profile on FamilyMemberHistory has Relationship as a Must Support field but code set is Must Support ([FHIR-35903](https://jira.hl7.org/browse/FHIR-35903))
1. Nutrition Order is not consistent with out Request pattern resources ([FHIR-35944](https://jira.hl7.org/browse/FHIR-35944))
1. QI Core Substance has code as Must Support but bound to example code set ([FHIR-35946](https://jira.hl7.org/browse/FHIR-35946))
1. Goal.target.measure and goal.target.date are both required so should be Must Support ([FHIR-35947](https://jira.hl7.org/browse/FHIR-35947))
1. Don't assign system values for tax id or other identifiers ([FHIR-35971](https://jira.hl7.org/browse/FHIR-35971))
1. Need practitionerRole in Encounter.participant.individual as it supports specialty taxonomy which is needed in some quality scenarios ([FHIR-36745](https://jira.hl7.org/browse/FHIR-36745))
1. Update PractionerRole.specialty value set binding to match US Core 5.0.0 ([FHIR-37365](https://jira.hl7.org/browse/FHIR-37365))
1. Update ServiceRequest to match US Core 5.0.0 ([FHIR-37447](https://jira.hl7.org/browse/FHIR-37447))
1. Update QI-Core to reference new US Core 5.0 Observation profiles ([FHIR-37457](https://jira.hl7.org/browse/FHIR-37457))
1. Create new QI-Core QuestionnaireResponse Profile consistent with US Core 5.0.0 ([FHIR-37458](https://jira.hl7.org/browse/FHIR-37458))
1. Create new Observation Clinical Test Result profile consistent with US Core 5.0.0 ([FHIR-37459](https://jira.hl7.org/browse/FHIR-37459))
1. Create new Observation Imaging Result Profile consistent with US Core 5.0.0 ([FHIR-37460](https://jira.hl7.org/browse/FHIR-37460))
1. Create Observation Sexual Orientation Profile consistent with US Core 5.0.0 ([FHIR-37461](https://jira.hl7.org/browse/FHIR-37461))
1. Create new Observation Social History Profile consistent with US Core 5.0.0 ([FHIR-37462](https://jira.hl7.org/browse/FHIR-37462))
1. Create new Observation Survey Profile Consistent with US Core 5.0.0 ([FHIR-37463](https://jira.hl7.org/browse/FHIR-37463))
1. Add new Conditions Problems and Health Concerns Profile and Encounter Diagnosis Profile consistent with US Core 5.0.0 ([FHIR-37464](https://jira.hl7.org/browse/FHIR-37464))
1. Update ObservationNotDone profile to indicate use for all observation profiles ([FHIR-37489](https://jira.hl7.org/browse/FHIR-37489))
1. Update QICore Observation Profile to indicate restricted use ([FHIR-37490](https://jira.hl7.org/browse/FHIR-37490))
1. Add full QI-Core Laboratory Result Observation Profile ([FHIR-37505](https://jira.hl7.org/browse/FHIR-37505))
1. Add Must Support for Procedure.usedReference ([FHIR-37532](https://jira.hl7.org/browse/FHIR-37532))
1. Add note to balloters for feedback in next ballot version ([FHIR-37535](https://jira.hl7.org/browse/FHIR-37535))
1. Update QDM to QI-Core Mapping section ([FHIR-37536](https://jira.hl7.org/browse/FHIR-37536))
1. Modify text on introduction page for QI-Core ([FHIR-37539](https://jira.hl7.org/browse/FHIR-37539))
1. Update Model Info ([FHIR-37579](https://jira.hl7.org/browse/FHIR-37579))
1. Encounter.hospitalization.dischargeDisposition binding - for QI-Core R5 is incorrect ([FHIR-37627](https://jira.hl7.org/browse/FHIR-37627))
1. TaskNotDone Task.code binding to task-code value set should be preferred, not example ([FHIR-37656](https://jira.hl7.org/browse/FHIR-37656))
1. Changes to Coverage profile ([FHIR-37669](https://jira.hl7.org/browse/FHIR-37669))
1. Remove CCN Number Identifier Slice from QI Core Practitioner as this only applies to an Organization ([FHIR-37751](https://jira.hl7.org/browse/FHIR-37751))
1. Adding ODH capability to QICore ([FHIR-37755](https://jira.hl7.org/browse/FHIR-37755))
1. Remove references for .subject in ObservationLab and ObservationClinicalTest ([FHIR-37782](https://jira.hl7.org/browse/FHIR-37782))
1. Small typo ([FHIR-37788](https://jira.hl7.org/browse/FHIR-37788))
1. Modify language in section 1.8 - Relationship to Other Initiatives ([FHIR-37806](https://jira.hl7.org/browse/FHIR-37806))
1. CCN system should use URL not OID ([FHIR-37900](https://jira.hl7.org/browse/FHIR-37900))
1. Put all Updates in Change tab ([FHIR-38077](https://jira.hl7.org/browse/FHIR-38077))
1. Blood Pressure Pattern Example ([FHIR-38112](https://jira.hl7.org/browse/FHIR-38112))
1. Inconsistency In Naming Profiles ([FHIR-38119](https://jira.hl7.org/browse/FHIR-38119))
1. Provide links to Example Source ([FHIR-38135](https://jira.hl7.org/browse/FHIR-38135))
1. POA value set codes ([FHIR-38181](https://jira.hl7.org/browse/FHIR-38181))
1. 2 Resource Profile name for Medication Not Requested / Service Not Requested are not align with other negation profiles ([FHIR-38182](https://jira.hl7.org/browse/FHIR-38182))
1. Suggest that examples that are CQL based be added to the QICore manual in addition to the FHIR based examples that already exist ([FHIR-38185](https://jira.hl7.org/browse/FHIR-38185))
1. QICoreProcedureType Value Set missing CLD ([FHIR-38204](https://jira.hl7.org/browse/FHIR-38204))
1. Consistency of multi-word element names ([FHIR-38213](https://jira.hl7.org/browse/FHIR-38213))
1. Allergy Example ([FHIR-38217](https://jira.hl7.org/browse/FHIR-38217))
1. Typo correction to Section 1.4 ([FHIR-38315](https://jira.hl7.org/browse/FHIR-38315))
1. Encounter.diagnosis reference ([FHIR-38316](https://jira.hl7.org/browse/FHIR-38316))
1. Typo correction to Section 2.2 ([FHIR-38360](https://jira.hl7.org/browse/FHIR-38360))
1. Typo correction to Section 9.1 ([FHIR-38363](https://jira.hl7.org/browse/FHIR-38363))
1. Defining URL should be anchored in THO. 1. ([FHIR-38548](https://jira.hl7.org/browse/FHIR-38548))
1. Defining URL should be anchored in THO. 2. ([FHIR-38549](https://jira.hl7.org/browse/FHIR-38549))
1. Defining URL should be anchored in THO. 3. ([FHIR-38550](https://jira.hl7.org/browse/FHIR-38550))
1. Defining URL should be anchored in THO. 4. ([FHIR-38551](https://jira.hl7.org/browse/FHIR-38551))
1. Defining URL should be anchored in THO. 5. ([FHIR-38552](https://jira.hl7.org/browse/FHIR-38552))
1. Defining URL should be anchored in THO. 6. ([FHIR-38553](https://jira.hl7.org/browse/FHIR-38553))
1. Defining URL should be anchored in THO. 7. ([FHIR-38554](https://jira.hl7.org/browse/FHIR-38554))
1. Defining URL should be anchored in THO. 8. ([FHIR-38555](https://jira.hl7.org/browse/FHIR-38555))
1. Defining URL should be anchored in THO. 9. ([FHIR-38556](https://jira.hl7.org/browse/FHIR-38556))
1. Defining URL should be anchored in THO. 10. ([FHIR-38557](https://jira.hl7.org/browse/FHIR-38557))
1. Defining URL should be anchored in THO. 11. ([FHIR-38558](https://jira.hl7.org/browse/FHIR-38558))
1. Defining URL should be anchored in THO. 12. ([FHIR-38559](https://jira.hl7.org/browse/FHIR-38559))
1. Defining URL should be anchored in THO. 13. ([FHIR-38560](https://jira.hl7.org/browse/FHIR-38560))
1. Defining URL should be anchored in THO. 14. ([FHIR-38561](https://jira.hl7.org/browse/FHIR-38561))
1. Defining URL should be anchored in THO. 15. ([FHIR-38562](https://jira.hl7.org/browse/FHIR-38562))
1. Defining URL should be anchored in THO. 16. ([FHIR-38563](https://jira.hl7.org/browse/FHIR-38563))
1. Defining URL should be anchored in THO. 20. ([FHIR-38567](https://jira.hl7.org/browse/FHIR-38567))
1. Defining URL should be anchored in THO. 21. ([FHIR-38568](https://jira.hl7.org/browse/FHIR-38568))
1. Defining URL should be anchored in THO. 22. ([FHIR-38569](https://jira.hl7.org/browse/FHIR-38569))
1. Defining URL should be anchored in THO. 23. ([FHIR-38570](https://jira.hl7.org/browse/FHIR-38570))
1. Defining URL should be anchored in THO. 25. ([FHIR-38572](https://jira.hl7.org/browse/FHIR-38572))
1. Defining URL should be anchored in THO. 27. ([FHIR-38574](https://jira.hl7.org/browse/FHIR-38574))
1. Consider topic, rather than reasonCode as the primary code path for Communication and CommunicationNotDone ([FHIR-38591](https://jira.hl7.org/browse/FHIR-38591))
1. Ensure negation profiles are disjoint ([FHIR-38788](https://jira.hl7.org/browse/FHIR-38788))
1. Provide consistent naming for QI-Core negation profiles ([FHIR-38850](https://jira.hl7.org/browse/FHIR-38850))
1. Update QICoreCommon Library ([FHIR-39164](https://jira.hl7.org/browse/FHIR-39164))
1. Update QDM to QI-Core Mappings for new terms for negation profiles ([FHIR-39307](https://jira.hl7.org/browse/FHIR-39307))
1. statusReason extension is unbounded ([FHIR-39361](https://jira.hl7.org/browse/FHIR-39361))



### STU4.1 Release with 1 Technical Errata for FHIR R4 (v4.1.1)


* [FHIR-35873](https://jira.hl7.org/browse/FHIR-35873): Corrected version-independent links to USCore throughout
* [FHIR-35802](https://jira.hl7.org/browse/FHIR-35802): Corrected negation examples and added guidance for usage of valueset-based negation

### STU4.1 Release for FHIR R4 (v4.1.0)


1. Broken Link for QUICK AdverseEvent actuality value set binding ([FHIR-23934](https://jira.hl7.org/browse/FHIR-23934))
1. Immunization.occurrence should remove the String choice ([FHIR-26407](https://jira.hl7.org/browse/FHIR-26407))
1. MedicationNotDispensed ([FHIR-26409](https://jira.hl7.org/browse/FHIR-26409))
1. Naming of QUICK vs QI-Core Logical View  ([FHIR-26592](https://jira.hl7.org/browse/FHIR-26592))
1. Medication list patient reported medications use Intent = Plan (not order) ([FHIR-26829](https://jira.hl7.org/browse/FHIR-26829))
1. wrong link in QDM to QICore mapping ([FHIR-27031](https://jira.hl7.org/browse/FHIR-27031))
1. Remove imagingStudy must support from the QICoreDiagnosticReportLab profile ([FHIR-27163](https://jira.hl7.org/browse/FHIR-27163))
1. Add TIN to QICore Organization Profile ([FHIR-27804](https://jira.hl7.org/browse/FHIR-27804))
1. DEQM Practitioner and DEQM Organization Profile should be added to QI Core ([FHIR-28157](https://jira.hl7.org/browse/FHIR-28157))
1. Patient resource generalpractitioner needs to consider PractitionerRole (https://jira.hl7.org/browse/FHIR-28220))
1. Can you add my affiliation? ([FHIR-28231](https://jira.hl7.org/browse/FHIR-28231))
1. change D.role to D.use in example with Encounter.diagnosis ([FHIR-28241](https://jira.hl7.org/browse/FHIR-28241))
1. Add MUST HAVE for MedicationRequest timing elements ([FHIR-28286](https://jira.hl7.org/browse/FHIR-28286))
1. Update Present On Admission in QDM to QI Core Mapping ([FHIR-29703](https://jira.hl7.org/browse/FHIR-29703))
1. Change mapping of \"Encounter, Performed\" code from Encounter.class to Encounter.type ([FHIR-29819](https://jira.hl7.org/browse/FHIR-29819))
1. QDM to QI-Core mapping for AdverseEvent error ([FHIR-30098](https://jira.hl7.org/browse/FHIR-30098))
1. Add QICoreModelInfo ([FHIR-30771](https://jira.hl7.org/browse/FHIR-30771))
1. Include US Core errata (3.1.1) to QI-Core Update process ([FHIR-31350](https://jira.hl7.org/browse/FHIR-31350))
1. Add MedicationDispense.whenPrepared MUST SUPPORT ([FHIR-31609](https://jira.hl7.org/browse/FHIR-31609))
1. Update QDM to QI-Core Mapping to address QDM 5.6 ([FHIR-31629](https://jira.hl7.org/browse/FHIR-31649))
1. Add guidance about use of references in profiles QI-Core inherits from US Core and FHIR ([FHIR-31738](https://jira.hl7.org/browse/FHIR-31738))
1. Update QDM to QI-Core mapping for ([FHIR-31740](https://jira.hl7.org/browse/FHIR-31740))
1. Profile Procedure NOT Done - why is element code not required ([FHIR-31929](https://jira.hl7.org/browse/FHIR-31929))
1. Procedure NOT Done - what is the intent of the valueset-reference in Code element ([FHIR-31930](https://jira.hl7.org/browse/FHIR-31930))
1. Procedure NOT Done - recorded does not have a clear description ([FHIR-31931](https://jira.hl7.org/browse/FHIR-31931))
1. Coverage.period shows in Differential but we cannot identify the change from FHIR Core ([FHIR-31932](https://jira.hl7.org/browse/FHIR-31932))
1. QI Core Observation.code binding is just example to LOINC ([FHIR-31933](https://jira.hl7.org/browse/FHIR-31933))
1. QI Core IG does not have a Table of Contents page ([FHIR-31935](https://jira.hl7.org/browse/FHIR-31935))
1. QDM to QI-Core mapping Section 8.1 correct text to QDM 5.6 ([FHIR-31974](https://jira.hl7.org/browse/FHIR-31974))
1. Adverse Event QDM-to-QI-Core mapping errata ([FHIR-31975](https://jira.hl7.org/browse/FHIR-31975))
1. QDM to Qi-Core mapping AllergyIntolerance ([FHIR-31976](https://jira.hl7.org/browse/FHIR-31976))
1. QDM to Qi-Core sections 8.4.1, 8.4.3 Assessment Order/Recommended ([FHIR-31977](https://jira.hl7.org/browse/FHIR-31977))
1. QDM to QI-Core mapping Communication, Performed ([FHIR-31978](https://jira.hl7.org/browse/FHIR-31978))
1. QDM to Qi-Core mapping for Device Order, Device Recommended ([FHIR-31979](https://jira.hl7.org/browse/FHIR-31979))
1. QDM to QI-Core mapping Diagnostic Study corrections ([FHIR-31980](https://jira.hl7.org/browse/FHIR-31980))
1. QDM to QI-Core mapping - Encounter ([FHIR-31981](https://jira.hl7.org/browse/FHIR-31981))
1. QDM to QI-Core mapping Immunization Administered status error ([FHIR-31982](https://jira.hl7.org/browse/FHIR-31982))
1. QDM to QI-Core mapping Intervention performed errors ([FHIR-31983](https://jira.hl7.org/browse/FHIR-31983))
1. QDM to QI-Core mapping Laboratory order and recommended error ([FHIR-31984](https://jira.hl7.org/browse/FHIR-31984))
1. QDM to QI-Core mapping Medication Administered error ([FHIR-31985](https://jira.hl7.org/browse/FHIR-31985))
1. QDM to QI-Core mapping Medication, Discharge error ([FHIR-31987](https://jira.hl7.org/browse/FHIR-31987))
1. QDM to QI-Core mapping update for Medication, Dispensed ([FHIR-31988](https://jira.hl7.org/browse/FHIR-31988))
1. QDM to QI-Core mapping Physical Exam Order and Recommended error ([FHIR-31989](https://jira.hl7.org/browse/FHIR-31989))
1. QDM to QI Core mapping changes for Procedure, Order, Procedure, Recommended and Procedure, Performed ([FHIR-31990](https://jira.hl7.org/browse/FHIR-31990))
1. QDM to QI-Core mapping - error in Immunization, Administered not done mapping ([FHIR-32005](https://jira.hl7.org/browse/FHIR-32005
1. QDM to QI-Core mapping for \"Medication, Order\" status constraints ([FHIR-32037](https://jira.hl7.org/browse/FHIR-32037
1. CommunicationNotDone code requires change in cardinality and modeling ([FHIR-32052](https://jira.hl7.org/browse/FHIR-32052))
1. DeviceRequestNotDone code binding and cardinality may require a specific slice for the eCQM use case ([FHIR-32053](https://jira.hl7.org/browse/FHIR-32053))
1. ImmunizationNotDone should allow indication an individual immunization was not performed and a slice to indicate none of the members of a value set was performed ([FHIR-32054](https://jira.hl7.org/browse/FHIR-32054))
1. MedicationNotAdministered requires ability to specify a single medication or an entire value set slice ([FHIR-32055](https://jira.hl7.org/browse/FHIR-32055))
1. MedicationNotDispensed should allow indication of a single medication not dispensed or a slice to indicate an entire value set was not dispensed ([FHIR-32056](https://jira.hl7.org/browse/FHIR-32056))
1. MedicationNotRequested should allow reference to a single medication not requested or a slice for a value set of all medications not requested ([FHIR-32057](https://jira.hl7.org/browse/FHIR-32057))
1. ObservationCancelled should allow reference to a single observation not performed or a slice for a value set for which none of the items were performed ([FHIR-32058](https://jira.hl7.org/browse/FHIR-32058))
1. ServiceNotRequested requires ability to specify a single service not requested or a slice for any one of a value set of services not requested ([FHIR-32059](https://jira.hl7.org/browse/FHIR-32059))
1. DiagnosticReportLab does not have Performer or Issued as Must Support even though the US Core Specification Does ([FHIR-32235](https://jira.hl7.org/browse/FHIR-32235))
1. How to reference TaskNotDone ([FHIR-32273](https://jira.hl7.org/browse/FHIR-32273))
1. Create QICorePresentOnAdmission value set ([FHIR-32378](https://jira.hl7.org/browse/FHIR-32378))
1. Add Must Support to Procedure.usedCode ([FHIR-32991](https://jira.hl7.org/browse/FHIR-32991))
1. Add Must Support for ServiceRequest.intent, MedicationRequest.intent, NutritionOrder.intent, NutritionOrder.status ([FHIR-33027](https://jira.hl7.org/browse/FHIR-33027))
1. Update identifiers throughout ([FHIR-33085](https://jira.hl7.org/browse/FHIR-33085))
1. Remove Authoring section ([FHIR-33260](https://jira.hl7.org/browse/FHIR-33260))



#### The following tickets listed below were incorporated from the **US Core errata (3.1.1)**:

* Add guidance for representing patient name suffix and previous patient name to the US Core Patient Profile ([FHIR-28129](https://jira.hl7.org/browse/FHIR-28129))
* Correct copy/paste error in Goal Profile ([FHIR-28109](https://jira.hl7.org/browse/FHIR-28109))
* Correct US Core Provider Speciality (NUCC) ValueSet to hide abstract grouping codes ([FHIR-27975](https://jira.hl7.org/browse/FHIR-27975))
* Added example of US Core Direct Extension to Practitioner-2 Example ([FHIR-27947](https://jira.hl7.org/browse/FHIR-27947))
* Corrected technical errors in pediatric profiles StructureDefinitions ([FHIR-27946](https://jira.hl7.org/browse/FHIR-27946))
* Corrected errors in DiagnosticReport Cardiology Example ([FHIR-27913](https://jira.hl7.org/browse/FHIR-27913))
* Update Federal Register link for OMB race and ethnicity category classifications. ([FHIR-27907](https://jira.hl7.org/browse/FHIR-27907))
* Clarified token search syntax ([FHIR-27897](https://jira.hl7.org/browse/FHIR-27897))
* Corrected US Core DocumentReference Profile to support multiple attachments ([FHIR-25778](https://jira.hl7.org/browse/FHIR-25778))
* Fix FHIRPath Expression in USCoreGoalTargetDate ([FHIR-27892](https://jira.hl7.org/browse/FHIR-27892))
* Fix FHIRPath Expression in USCoreProcedureDate ([FHIR-27887](https://jira.hl7.org/browse/FHIR-27887))
* Add omitted ge comparators to SearchParameters ([FHIR-27893](https://jira.hl7.org/browse/FHIR-27893))
* Remove Must Support References to non US Core Profiles ([FHIR-27876](https://jira.hl7.org/browse/FHIR-27876))
* Add missing reaction to the US Core AllergyIntolerance Profile ([FHIR-27867](https://jira.hl7.org/browse/FHIR-27867))
* Clarify reference to US Core Patient in Vitals Signs Profiles ([FHIR-27857](https://jira.hl7.org/browse/FHIR-27857))
* Corrected US Core Pulse Oximetry Profile component.valueQuantity.code and component.valueQuantity.unit min from 0 to 1 to be consistent with the valueQuantity constraints within US Core ([FHIR-27846](https://jira.hl7.org/browse/FHIR-27846))
* Correct UCUM Unit in US Core Pulse Oximetry Profile Text Summary ([FHIR-27845](https://jira.hl7.org/browse/FHIR-27845))
* Update Procedure Codes Value Set to include ICD-10 PCS codes ([FHIR-27836](https://jira.hl7.org/browse/FHIR-27836))
* Update Procedure Codes Value Set to include CDT codes ([FHIR-27737](https://jira.hl7.org/browse/FHIR-27737))
* Clarify that pediatric vital sign percentile Observations should reference growth chart ([FHIR-27549](https://jira.hl7.org/browse/FHIR-27549))
* Added Missing US core Head Occipital-frontal Circumference Percentile Profile ([FHIR-27542](https://jira.hl7.org/browse/FHIR-27542))
* Correct requirements for supporting CLIA identifiers ([FHIR-27158](https://jira.hl7.org/browse/FHIR-27158))
* Change Description of ICD-10-PCS Value Set ([FHIR-27116](https://jira.hl7.org/browse/FHIR-27176))
* Correct AllergyIntolerance guidance for verificationStatus ([FHIR-27096](https://jira.hl7.org/browse/FHIR-27096))
* Fix example US Core heart-rate example ([FHIR-27086](https://jira.hl7.org/browse/FHIR-27086))
* Review period comments Update smoking status codes to align with USCDI ([FHIR-27082](https://jira.hl7.org/browse/FHIR-27082))
* Fix invariant provenance-1 ([FHIR-27065](https://jira.hl7.org/browse/FHIR-27065))
* Fix invalid json snippet ([FHIR-27001](https://jira.hl7.org/browse/FHIR-27001))
* Review period comments Remove Provenance requirement from Medication, Location, Practitioner, PractitionerRole, and Organization and correct copy and paste error to Medication and Provenance searchType support in CapabilityStatement ([FHIR-26840](https://jira.hl7.org/browse/FHIR-26840)),([FHIR-28161](https://jira.hl7.org/browse/FHIR-28161))
* Correction on USCDI Table change MedicationStatement to MedicationRequest and remove references to MedicationStatement in the Medication Profile and CapabilityStatements ([FHIR-26840](https://jira.hl7.org/browse/FHIR-26840))
* Clarify that US Core Location/PractitionerRole are not being referenced by other resources ([FHIR-26840](https://jira.hl7.org/browse/FHIR-26840))
* Correct editing error restoring Write and Operation capability guidance into DocumentReference QuickStart ([FHIR-26840](https://jira.hl7.org/browse/FHIR-26840))
* Clarify guidance that servers SHALL support search with status if status required ([FHIR-26840](https://jira.hl7.org/browse/FHIR-26840))
* Correct canonical URL for ImplementationGuide ([FHIR-26686](https://jira.hl7.org/browse/FHIR-26686))
* Correct system URI for ICD-10 procedure codes ([FHIR-26679](https://jira.hl7.org/browse/FHIR-26679))
* Fix invariant us-core-1 ([FHIR-26605](https://jira.hl7.org/browse/FHIR-26605))
* Change valueCode min from 0 to 1 for US Core Birth Sex Extension and valueBoolean min from 0 to 1 forUS Core Direct email Extension ([FHIR-26459](https://jira.hl7.org/browse/FHIR-26459))
* Change valueQuantity min from 1 to 0 for US Core Pediatric BMI for Age Observation Profile and US Core Pediatric Weight for Height Observation Profile ([FHIR-26363](https://jira.hl7.org/browse/FHIR-26363))
* Add page contents to Clinical Notes and Basic Provenance pages ([FHIR-25785](https://jira.hl7.org/browse/FHIR-25785))
* Fix duplicate URL causing validation failure. ([FHIR-25536](https://jira.hl7.org/browse/FHIR-25536))
* Fix Invariant us-core-8 ([FHIR-25459](https://jira.hl7.org/browse/FHIR-25459))
* Corrected the wording should support to shall support in Clinical Notes Guidance ([FHIR-25455](https://jira.hl7.org/browse/FHIR-25455))
* Fix Invariant us-core-8 to allow for Data Absent Reason Extension on Patient name.([FHIR-25249](https://jira.hl7.org/browse/FHIR-25249))
* Fix Link to LOINC LP29708-2 ([FHIR-25213](https://jira.hl7.org/browse/FHIR-25213))
* Corrected guidance for conveying Patient-Reported medications ([FHIR-25035](https://jira.hl7.org/browse/FHIR-25035))

### STU4 Release for FHIR R4 (v4.0.0)


* Created negation profiles
* Added patterns pages and CQL examples
* Corrections throughout
* Updated QDM-to-QI-Core mapping
* Added negation reason value set and bindings

### STU4 Ballot for FHIR R4 (v3.3.0)


* Updated profiles to be based on FHIR R4 and US Core STU 3
* #22645 Added profiles on Immunization and Evaluation
* #15012 Added a profile on NutritionOrder
* #20727 Updated Observation documentation to provide clarity on use of FHIR and US Core profiles
* #20610 Created the notDone extension and modified the DeviceUseStatement profile to use it; added the DeviceRequest profile, use the doNotPerform extension
* #22646 Relaxed Must Support requirement on some fields of Immunization and ImmunizationRecommendation profiles
* #14991 Added an example of using body position with an Observation

### STU3.2 Release for FHIR STU3 (v3.2.0)


* Updated profiles to be based on US Core 2.0.0
* Derived Encounter and PractitionerRole profiles from US Core profiles

### STU3 Release for FHIR STU3 (v3.1.0)


* Added profile for PractitionerRole and removed Practitioner.role extension
* Added profile for Task
* Established pattern for representing QDM Principal Diagnosis in Encounters
* Relaxed conformance requirements from all profiles to profiles that are relevant to a particular use case

### STU3 Ballot for FHIR STU3 (v2.1.0)


* Incorporates ballot reconciliation from all comments from the September 2016 ballot which have been applied to FHIR 3.0 and US Core Release 1.0.1
* Includes mapping to QDM Version 5.3 Annotated available at: https://ecqi.healthit.gov/qdm
* Includes an updated Mapping table from the QI-Core metadata to QDM 5.3
* Includes a direct mapping from QDM version 5.3 to QI Core

### STU2 Release for FHIR STU3 (v2.0.0)


* Updated to FHIR STU3 (3.0.1)
* Changed from Universal Realm to US Realm
* Derived from US Core profiles where possible
* Added support for Claim and Coverage resources
* Changed AdverseEvent profile to use the base resource
* Numerous typographical and technical errors corrected

### STU2 Ballot for FHIR STU3 Ballot (v1.6.0)


* Moved out of main FHIR publication package to its own home
* Updated QI-Core profiles for changes to underlying specification
* Added an additional profile on Condition
* The QUICK logical model is included

### STU1 Release for FHIR DSTU2 (v1.0.2)

DSTU 1 (Permanent home)

### DSTU1 Preview for FHIR STU1 (v1.0.0)

DSTU1 Preview

### DSTU1 Ballot for FHIR STU1 (v0.5.0)

DSTU1 Ballot
