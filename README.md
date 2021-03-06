# Other Requirements

Adds an object to describe other requirements to participate in a contracting process.

## Legal context

In the European Union, this extension's fields correspond to [eForms BG-705 (Other Requirements)](https://github.com/eForms/eForms), although not all the fields have been implemented yet. See [OCDS for the European Union](http://standard.open-contracting.org/profiles/eu/master/en/) for the correspondences to Tenders Electronic Daily (TED).

## Example

```json
{
  "tender": {
    "otherRequirements": {
      "requiresStaffNamesAndQualifications": true,
      "reservedParticipation": [
        "shelteredWorkshop"
      ],
      "qualificationSystemConditions": [
        "The candidates are required to comply with all the technical and financial requisites listed on the National Procurement portal: https://procurement.example.org/requisites",
        "The candidates are required to create an electronic profile on https://procurement.example.org."
      ],
      "qualificationSystemMethods": [
        "Pre-qualification questionnaire",
        "Standard test, based on the results of the pre-qualification questionnaire"
      ],
      "reductionCriteria": "The candidates will be selected according to their technical, financial and legal capacity to undertake the works described in the present notice. More details on the criteria can be found in section 4.3 of the PCG."
    }
  }
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

## Changelog

### 2020-04-24

* Add `minProperties`, `minItems` and/or `minLength` properties.

This extension was originally discussed as part of the [OCDS for EU profile](https://github.com/open-contracting-extensions/european-union/issues) and in [pull requests](https://github.com/open-contracting-extensions/ocds_otherRequirements_extension/pulls?q=is%3Apr+is%3Aclosed).
