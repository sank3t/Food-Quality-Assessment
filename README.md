## Food-Quality-Assessment

This online hackathon is hosted by [MachineHack](https://www.machinehack.com/course/food-quality-assessment-risk-analysis/).

### Objective
 To build a predictive model for conducting the inspection on a facility (type of site) to save the time of the food inspection team before conducting the inspection.

### Dataset Description

* #### Features -

  **ID:** A unique id for each inspection

  **Date:**  The date at which the inspection was done in a particular facility

  **LicenseNo:** De-identified license number for a particular facility

  **FacilityID:** De-identified unique facility id  for a facility

  **FacilityName:** The encoded name of a facility

  **Type:** The type of the facility being inspected

  **Street:** The encoded street where the facility is located

  **City:** The encoded city where the facility is located

  **State:** The encoded state where the facility is located

  **LocationID:** An encoded location feature.

  **Reason:** The primary reason for the inspection

  **SectionViolations:** Laws violated by the facility

  **RiskLevel:** The level of risk the facility possesses to the consumers.

  **Geo_Loc:** De-identified geo location of the facility

  **Inspection_Results:** The result of the inspection (target attribute)
    * Encoded value description
    ```
    0: FACILITY CHANGED
    1: FAIL
    2: FURTHER INSPECTION REQUIRED
    3: INSPECTION OVERRULED
    4: PASS
    5: PASS(CONDITIONAL)
    6: SHUT-DOWN
    ```
