| NCBI Field            | BOLD Field                                           | Required? |
|-----------------------|------------------------------------------------------|-----------|
| ACCESSION             | genbank_accession                                    | N         |
| AMPLIFICATION_FORWARD | seq_primers                                          | Y         |
| AMPLIFICATION_REVERSE | seq_primers                                          | Y         |
| CENTER_NAME           | sequencing_centers                                   | Y         |
| CENTER_PROJECT        | [arbitrary value]                                    | Y         |
| GENE_NAME             | marker_codes                                         | Y         |
| ORGANISM NAME         | species_name                                         | Y         |
| PRIMER                | [not given]                                          | N         |
| PRIMER_CODE           | [not given]                                          | N         |
| PROGRAM_ID            | [not given, but can usually be pulled from ABI file] | Y         |
| RUN_DATE              | run_dates                                            | N         |
| SOURCE_TYPE           | ["G" for Genomic DNA]                                | Y         |
| SPECIES_CODE          | species_name                                         | Y         |
| STRATEGY              | ["BARCODE"]                                          | Y         |
| SUBMISSION_TYPE       | ["NEW" or "UPDATE"]                                  | Y         |
| TEMPLATE_ID           | processid                                            | Y         |
| TRACE_END             | ["F", "R", or "N"]                                   | Y         |
| TRACE_FILE            | trace_links                                          | Y         |
| TRACE_FORMAT          | [pulled from trace file]                             | Y         |
| TRACE_TYPE_CODE       | ["PCR"]                                              | Y         |