# Terminology server
This is a terminology server prepackaged with the currently published Belgian terminologies.

The docker image contains all that is needed for deployment, except the SNOMED cache files. It meets the criteria and specifications to ue with the FHIR publication and validation systems.

More information is available [from the HL7 Europe documentation](https://hl7-eu.github.io/tx.hl7europe.eu/) as well as from the [HL7 Confluence page on running the server](https://confluence.hl7.org/spaces/FHIR/pages/79503408/Running+your+own+copy+of+tx.fhir.org).



## How to use:

* Clone the repository
* Download any the terminology cache files from https://storage.googleapis.com/tx-fhir-org into the txcache1/fhir-server
* run `docker compose up` after optionally adjusting any settings
* Create an [issue](./issues) if you need a different package, cache update or release


