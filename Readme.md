## Minor allele Frequency considering only homozygous sites and Heterozygousity filtering 


## Keeps sites only if het_frequency < 0.5 * hom_maf

How to run:

python HomoMAFfiltering.py pathtovcf pathtofilteredvcf

e.g. python HomoMAFfiltering.py /work/schnablelab/nikees/SAP_imputed.vcf /work/schnablelab/nikees/SAP_imputed_filtered.vcf
