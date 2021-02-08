[Jira](https://jira.arcus.chop.edu:8443/browse/ADP-431#add-comment)

### 2021_02_08
* I can compute a [union of pathogenic vars](https://github.com/samesense/TIL/blob/master/gcp/bq/Pathogenic.md#union-of-results) that can be [left joined with the variants](https://github.com/samesense/TIL/blob/master/gcp/bq/Variant_queries.md#select-pathogenic-variants-and-cross-ref-variant-table)
* **Next** I need to annotate hgmd indels, and add them to their own indel table.
* Update zygosity function to consider 1/2 as het. 2/2 as hom. I will no longer be matching 0,1,2,3 to the allele
