# Northwestern University Local Authorities (NULA)

This is an ongoing list of the local authorities in the Northwestern University catalog and how they are mapped to LCSH.

This list owes a considerable amount to the work done to map LCSH headings at the Chicago History Museum: https://libguides.chicagohistory.org/blog/LCSH-to-Local-Headings-Map and the resources listed below. 

Questions are welcome and can be sent to jamie.carlstone@northwestern.edu

## Instructions
Northwestern uses Alma/Primo. 
1. A new authority vocabulary was defined in Alma. Instructions for that process are available here: https://knowledge.exlibrisgroup.com/Alma/Product_Documentation/010Alma_Online_Help_(English)/Metadata_Management/060Working_with_Authority_Records#Adding_a_Local_Authority_Definition 
2. The original heading from LCSH is copied from the Community Zone into the Institution Zone as a NULA heading. The normalization rule AuthorityHeadingTemplate edits some of the heading, but manual work is also required.
3. MARC Record is edited according to similar standards outlined in the CHM libguide. The 450 $w nne is used instead of 450 $w ane.
4. Build a set of all bibliographic records that use the LCSH heading. Run the normalization rule on this set. Normalization rules are included in this repository. There is a normalization rule generator available at https://github.com/jdcar/generate-normalization-rule. 
 
## List of Resources
| Resource Name | Abbreviation | Link |
| ------ | ----- | ------ |
| Archives For Black Lives in Philadelphia | A4BLiP | https://archivesforblacklives.wordpress.com/resources/
| Chicago History Museum | CHM | https://libguides.chicagohistory.org/blog/LCSH-to-Local-Headings-Map
| Homosaurus | Homosaurus | https://homosaurus.org/
| Peoples of the Historical Slave Trade | | https://docs.enslaved.org/controlledVocabulary/ | 

 
## List of Headings
The list of headings was moved into the folder \NULA\Headings
With the LCSH updates about slavery, it was no longer necessary to make local changes to those headings. The list of the former NULA headings is retained in the file \NULA\Headings\former-local.txt