# ARCWAY-to-SpecIF-Exporter
Exports a model created in [ARCWAY Cockpit](http://www.arcway.com/) to SpecIF. All diagrams ("plans"), model elements and requirements together with their relations are exported; [examples](http://specif.de/#beispiele) of generated models can be seen here. Diagrams are exported as scalable vector graphics (SVG); the classes (types), resources (artefacts, objects) and statements (relations) in [SpecIF format](https://github.com/GfSE/SpecIF).

## Installation
The exporter is a script for the Apache Velocity template engine built into ARCWAY Cockpit. Install it using the properties dialog of 'Reports' ('Berichtsvorlagen'), which is accessible via context menue, within an ARCWAY Cockpit project.

## Usage
Once installed and initiated, the report generator creates a file 'projectname.specif' and a folder 'files_and_images' with all referenced diagrams. Both must be packed in a ZIP-container 'projectname.specifz' so that the SpecIF viewer can import the data. 

## Examples
These SpecIF files have been generated from an ARCWAY Cockpit model:
- [Integrated Process- and IT-Documentation](https://specif.de/examples/IT-Documentation.specifz), per [SpecIF-Viewer](https://specif.de/apps/view.html#import=%22../examples/IT-Documentation.specifz%22).
- [Integrated Specification of a Dimmer](https://specif.de/examples/Dimmer.specifz), per [SpecIF-Viewer](https://specif.de/apps/view.html#import=%22../examples/Dimmer.specifz%22).

## Acknowledgements
This work has been sponsored by [enso-managers gmbh](http://enso-managers.de), Berlin
