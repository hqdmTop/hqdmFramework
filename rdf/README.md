# HQDM as RDF

The [MagmaCore](https://github.com/gchq/MagmaCore) library can be used to create HQDM models as RDF in a triple-store, and it is useful to include a version of the HQDM ontology as RDF so that queries depending on the entity-type hierarchy can be executed.

## Versions

### 0.0.1-alpha

- This is a first attempt at a basic RDF mapping to support SPARQL queries that need the entity-type hierarchy. It also includes an initial attempt at defining the HQDM properties. As an `alpha` version be aware that it may change completely before `beta` and final release as version `0.0.1`