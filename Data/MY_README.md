# CapstoneProject

note: the data analysis is only in Capstone-analysis-initial and the rest just have code that has not been analysed because it has been copied and pasted but with the right column replaced and the code makes more sense. There is one issue where I forgot to change Fixed to a t.test.

data link: https://datadryad.org/stash/dataset/doi:10.5061%2Fdryad.171q5
data citation: Ilska, Joanna et al. (2018), Data from: Genetic characterization of dog personality traits, Dryad, Dataset, https://doi.org/10.5061/dryad.171q5


article link: https://academic.oup.com/genetics/article/206/2/1101/6064288?login=true
article citation: Joanna Ilska, Marie J Haskell, Sarah C Blott, Enrique Sánchez-Molano, Zita Polgar, Sarah E Lofgren, Dylan N Clements, Pamela Wiener, Genetic Characterization of Dog Personality Traits, Genetics, Volume 206, Issue 2, 1 June 2017, Pages 1101–1111, https://doi.org/10.1534/genetics.116.192674


article quiz link: https://www.sciencedirect.com/science/article/pii/S0168159114001099
article quiz citation: Lofgren S E, Wiener P, Blott S C, Sánchez Molano E, Woolliams J A et al. , 2014 Management and personality in the labrador retriever dogs. Appl. Anim. Behav. Sci. 156: 44–53, https://www.sciencedirect.com/science/article/pii/S0168159114001099

from the article that has the quiz:
"The C-BARQ questionnaire consists of 102 questions pertaining to dog behaviour, divided into seven sections. The sections pertain to Training and obedience (8 questions), Aggression (25), Fear and anxiety (19), Separation-related behaviour (8), Excitability (6), Attachment and attention seeking (6), and Miscellaneous (Barking, chasing, unusual behaviours, etc.) (28)."

#Gender (0=male, 2=female) + Neuter status (0=entire, 1=fixed)
0 = entire male, 1 = fixed male, 2 = entire female, 3 = fixed female

#Age (days)
#Role/WM2 (0=Gundog or 1=Pet, 2=Showdog)
#Housing/inout (1=Indoor, 2=Indoor/Outdoor, 3=Outdoor)
#Exercise/timeEx (1-4  hrs)
#Health (0=some health problem, 1=no health problem)
#coat color (0 black, 1 yellow, 2 chocolate) 

set A is described by the article but Set B is not directly described

all below between 1 and 5:

*SetA:
Agitated (level of agitation when ignored)
Attenseek (attention)
Bark (barking tendency (assuming comparatively to other dogs))
Excite (excitement)
Fetch (how well does the dog fetch)
HO_Fear (Human and Object Fear)
NoiseF (Noise Fear)
NO_Agg (Non-owner-directed Aggression)
O_Agg (Owner-directed Aggression)
SepAnx (Separation Anxiety)
Train (trainability)
UnBeh (Unusual Behavior)

*SetB:
HS_StrngDirAgg 
HS_OwnDirAgg
HS_StrngDirFear
HS_NonSocFear
HS_DogDirAggression
HS_DogDirFear
HS_SepRelBeh
HS_Attach
HS_Train
HS_Chase
HS_Excit
HS_Pain
HS_DogRiv
HS_EnLevel

