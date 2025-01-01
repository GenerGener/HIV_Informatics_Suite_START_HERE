# HIV_Informatics_STARTHERE
Howdy! You've reached the HIV Informatics Landing Page. The tools/resources here are designd to help you, the HIV researcher/clinician/community member maximize information extraction from samples with suspected HIV. The audince is assumed to know at least a bit about nucleic acid sequencing and "basic" HIV biology. I use bunny ears here because I found a bunch of new insights from revisiting this 40+ year-old virus with state-of-the-art sequencing methods. It's my hope that what I found doesn't sit in the Texas Medical Center stacks or one of a handful of bookshelves collecting dust. HIV's been around long enough, and together we can carry home the task of making it an historical problem, instead of one affecting communities across the globe.

# Tools/resources to facilitate the analyses of HIV squences

Tools/resources marked with asterisks (*) may have utility in non-HIV systems.

[HIV-1_mRNA_Atlas](https://github.com/GenerGener/HIV-1_mRNA_Atlas) - Standardized HIV-1 mRNA models[^1][^2][^3].

## Beta (working): 

[AtlasMaker*](https://github.com/GenerGener/AtlasMaker) - A species-agnostic method for reference-guided mRNA modeling.

[UTR_Checker](https://github.com/GenerGener/UTR_Checker) - Assess for U3-R-U5 presence in user-provided HIV sequences.

[UTR_Maker*](https://github.com/GenerGener/UTR_Maker) - Make 5' and 3' UTRs from annotated cDNA mRNA transcript models.

## Alpha (in development):

[AtlasMatcher*](https://github.com/GenerGener/AtlasMatcher) - Determine the extent to which a user's cDNA matches a given model set. It is designed with HIV-1 in mind, but may be absreacted for other genomic loci.

[AtlasAnnotator*](https://github.com/GenerGener/AtlasAnnotator) - Annotate AtlasMaker output with HIV-1 Atlas v1.0 GenBank annotations.

[SpliceChecker*](https://github.com/GenerGener/SpliceChecker) - Check HIV cDNA against HIV-1 Atlas v1.0.

[HIV_profiler*](https://github.com/GenerGener/HIV_profiler) - Use locus segmentation to inform HIV mRNA expression level estimation from sequencing data.

# Miscellaneous genomics programs (all beta)
[ONT_homopolymer_screen](https://github.com/GenerGener/ONT_homopolymer_screen)

[TelomereFinder](https://github.com/GenerGener/TelomereFinder)

[hashycat](https://github.com/GenerGener/hashycat)

[^1]: Gener, Alejandro R., Kimata, Jason T. Full-coverage native RNA sequencing of HIV-1 viruses. bioRxiv. 2019/01/01. doi: 10.1101/845610.

[^2]: Gener, A. R., Klotman, P. E., Danesh, F. R., Cijiang He, J., Kimata, J. T., Lupski, J. R., & Ross, M. J. (2021). HIV informatics. Baylor College of Medicine Integrative Molecular and Biomedical Sciences Graduate Program.

[^3]: Gener, A. R. (2022). Anticipating HIV drug resistance with appropriate sequencing methods. AIDS, 36(1). https://journals.lww.com/aidsonline/Fulltext/2022/01010/Anticipating_HIV_drug_resistance_with_appropriate.16.aspx.
