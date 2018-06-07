There are several tools in this directory for PnP server running in  DNA-C and APIC-EM

The first is for DNAC.
* DNAC-PnP-BulkConfig: Takes an xls spreadsheet of devices + variables and calls a creates a rule


The final three are APIC-EM
* PnPConfigTemplator: example scripts using jinja2 templates.
The templates are hierachical.  There is a base template, then a template for a 1-2-3 switch stack is built based on the base.
Shows a lot of the power of jinja2; loops, blocks etc

* PnPFileSync: keeps config, template and images files in sync with controller.  User can edit config files off box, then sync to APIC-EM
* PnPWatch


