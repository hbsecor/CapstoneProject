#Genotype files in binary Plink format
#Autosomes
#data885autosome_maf0.01_remove_hwe_excess_shortIDs.bed
#data885autosome_maf0.01_remove_hwe_excess_shortIDs.bim
#data885autosome_maf0.01_remove_hwe_excess_shortIDs.fam (this is a dummy file, just to allow Plink functions)

#X chromosome
#females
#data885X_maf0.01_hweqc_females_shortIDs.bed
#data885X_maf0.01_hweqc_females_shortIDs.bim
#data885X_maf0.01_hweqc_females_shortIDs.fam (this is a dummy file, just to allow Plink functions)

#males
#data885X_maf0.01_hweqc_males_shortIDs.bed
#data885X_maf0.01_hweqc_males_shortIDs.bim
#data885X_maf0.01_hweqc_males_shortIDs.fam (this is a dummy file, just to allow Plink functions)


#PHENOTYPES files: "data885_ALL_PHENOTYPES" "data885X_FEMALES_PHENOTYPES" "data885X_MALES_PHENOTYPES"
#Ignore sex in "data885_ALL_PHENOTYPES" file. Correct sex in "Covariates_revised_ids" file (see below)
#Include the following traits, in order (fields 6-17)
#Agitated
#Attention
#Barking
#Excitability
#Fetching
#HOFear
#NoiseFear
#NOAggression
#OAggression
#SepAnxiety
#Trainability
#Unusual

#Covariates file ("Covariates_revised_ids") includes the following fields:
#ID (need to remove this for Gemma analysis)
#Gender (0=male, 2=female)
#Neuter status (0=entire, 1=neutered)
#Age (days)
#Role (0=Pet or 1=Showdog, 2=Gundog)
#Housing (1=Indoor, 2=Indoor/Outdoor, 3=Outdoor)
#Exercise (1-4)
#Health (0=some health problem, 1=no health problem)

