# linked-ui
Dynamically mapping UI components to a Linked Data representation

## Aim
* Simplify UI definition on top of Linked Data
* Allow dynamic data-centric UI adaptation
* Allow UI migration/adaptation between devices/modes/contexts through declarative means
* Possibly allow "free" two-way data-binding

## Techniques
* Representation of UI language through Linked Data vocabularies
  * XML DOM
  * JSON
* Declarative definition of mapping from Linked Data source(s)
  * SPARQL Views
  * Ontology Mapping
  
## Existing UI Side Libraries that can be used
* AngularJS (JSON <-> HTML, two-way data mapping)
  * https://angularjs.org/
  * Angular GMaps: http://angular-ui.github.io/angular-google-maps/#!/use
* Web Components (XML <-> UI, potentially two-way data mapping, through shadow DOM)
  * Google WCs: http://googlewebcomponents.github.io/
  * GMaps WC: http://googlewebcomponents.github.io/google-map/components/google-map/
