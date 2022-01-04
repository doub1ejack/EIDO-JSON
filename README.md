Cloned from the 911.gov repo so I could use...

## [» Easily Browse the EIDO Schema](https://json-schema.app/view/%23?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdoub1ejack%2FEIDO-JSON%2Fmain%2FSchema%2Fopenapi.json)

.. particularly the [Schema Properties](https://json-schema.app/view/%23/%23%2Fdefinitions%2FComponents/%23%2Fdefinitions%2FSchemas?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdoub1ejack%2FEIDO-JSON%2Fmain%2FSchema%2Fopenapi.json).

(thank you jasonformatter.org)
.

## See also:

- https://www.nena.org/page/i3_Stage3
- https://nenawiki.org/wiki/EIDO_(Emergency_Incident_Data_Object)

## About NENA-JSON-EIDO

NENA WG JSON based EIDO

- The NENA STA describing the EIDO is located in ".\Documentation"
- Example EIDO instances can be found in ".\Samples"
- The openapi.yaml in ".\Schema" can be used to generate code to serialise and deserialise EIDO instances. It use converted types from NIEM.
- Converted types from NIEM can be found in the "[NiemNamespacePrefix].yaml" files found in ".\Schema\NIEMComponents"
- JSON-LD context providing mapping for each of these NIEM types can be found in the "[Typename]Context.jsonld" files found in ".\Schema\JSON-LD_Contexts"
