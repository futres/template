# template
To use these templates, first see the **templates.csv** for the terms, their definitions, and descriptions. Users looking to contribute data to the FuTRES project can then download the template most appropriate for their data (**user-download-neo** for neontological, **user-download-paleo** for paleontological, or **user-download-zooarch** for zooarchaeological). This provides a blank slate with the appropriate field names, making it easier to reformat your data for ingestion into FuTRES.

In the very near future, you will be able to create custom templates using GEOME (add link when that is ready).

You can download the template file directly or clone the repo to your desktop and edit it locally.

## Semantic Versioning of Releases
A release has three numbers separated by periods, like ```1.2.3```

The numbers separated by the dots have the following significance:
 * First letter (1): a major release that would normally require re-loading all data in GEOME.  This would happen, for example, if we change the root-most leaf node of identifiers (e.g. replacing materialSampleID with diagnosticID).
 * Second letter (2): if there is a change to terms that are REQUIRED (either new or removed).
 * Third letter (3): Any change to non-required terms or definitions or addition of terms that are not required.

For example, if the current release is ```1.2.1``` and we add a new required term, the new release will be ```1.3.0```.  However, if we add a new term that it is not required, the new release would be ```1.2.2```.  If we decide to change data model more fundamentally, such as adding diagnosticID as the primary key the new release would be ```2.0.0```

Note that using this model, all releases will be final releases, so no need to use ```pre release```.  
 
