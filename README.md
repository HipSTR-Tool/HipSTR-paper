# HipSTR-paper
Various datasets produced in the HipSTR paper


File | Description
---- | ----
 high_confidence_denovos.vcf.gz | VCF file containing STR genotypes for samples NA12877, NA12878, NA12891 and NA12891 at 358 loci. For each of these loci, HipSTR identified a de novo allele in NA12878 that was replicable in 2 orthogonal Illumina datasets.
 str_reference.hg19.bed.gz | HipSTR BED file used to identify *de novo* STR mutations across the human genome. The STR coordinates are for  the *hg19* assembly and the file needs to be decompressed with *gunzip* prior to using it as input with HipSTR.
 marshfield_regions.bed | HipSTR BED file used to genotype Marshfield regions in the benchmarking comparison for tools that are **aware** of STR repeat coordinates 
 marshfield_regions.15pad.bed | HipSTR BED file used to genotype Marshfield regions in the benchmarking comparison for tools that are **unaware** of STR repeat coordinates. Relative to the above file, the start and end coordinates are padded by 15bp to increase the probability of capturing indels near the STR region
