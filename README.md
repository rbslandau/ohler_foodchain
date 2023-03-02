# Repo for the publication: Land use changes biomass and temporal patterns of insect cross-ecosystem flows


This repo contains the R code and data for the related manuscript submitted for publication.

Written by Katharina Ohler, revised by Verena C. Schreiner and Ralf B. Schäfer

## Content overview: 

### Folder data_preparation: Contains R Markdown and all raw data used to prepare the data
  - Data_prep.Rmd: R Markdown document detailing all steps of data preparation
  
 1. biomass_abundance_data: All raw data to calculate biomass and abundance  
     1.1 biomass_emergence_93.csv: Raw data for dry mass of emergent aquatic insect families per sample  
   1.2 emergence_identification_92.csv: Number of all organisms identified in samples collected with emergence traps  
   1.3 emergence_NA_0_92.csv: List of all samples with information on missing samples, identified samples and samples, in which emergence = 0  
  1.4 no_trap_days.csv: Sampling days per sample  
  1.5 no_trap_days_NA.csv: List with events where traps were destroyed by vandalism or heavy rainfall and, thus, no insects were collected

 2. land_use_related_drivers_data: All habitat and physicochemical raw data  
  2.1 habitat.csv: Habitat variables  
  2.2 phys_chem.csv: Physicochemical land use-related-drivers of emergent aquatic insects  

 3. pesticide_data: All raw data to calculate pesticide toxicity  
  3.1 0_ANA_Substances.txt: CAS number of pesticides  
  3.2 3_ANA_ConcentrationTox.csv: Concentration of pesticides in event and grab samples  
  3.3 06_Schwebstoffilter GC_LC.csv: Fraction of organic carbon in the samples of suspended particles  
  3.4 20191111_KgM_SPM-Extrakte_2018_final_nur_RLP.csv: Concentration of pesticides on suspended particles  
  3.5 EC50_version_190326.csv: EC50 values not found in Standartox  
  3.6 KGM_freshwater_invertebrate_XX50.rds: EC50 from Standartox
  3.7 Samples_forest_2: Concentration of pesticides in grab samples of forested sites  
  
4. trait_data: All trait data  
  4.1 generation_time_spear.csv: Raw data of trait generation time of emergent aquatic insects  
  4.2 Trait_DB_EU_corrected.rds: Trait size of emergent aquatic insects

 
### Folder statistics_biomass_emergence: Contains R Markdown and all data used in data analysis
  - Data_analysis.Rmd: R Markdown document detailing all steps of data analysis

 1.  HGAM_abundance: All fits of HGAMs for abundance     
  1.1 num_position_family_I.RData: Fit of HGAM for family abundance with different group-level trends  
  1.2 num_position_family_S.RData: Fit of HGAM for family abundance with similar group-level trends  
  1.3 num_position_I.RData: Fit of HGAM for total abundance with different group-level trends  
  1.4 num_position_order_I.RData: : Fit of HGAM for order abundance with different group-level trends  
  1.5 num_position_order_S.RData: Fit of HGAM for order abundance with similar group-level trends  
  1.6 num_position_S.RData: Fit of HGAM for total abundance with similar group-level trends  
  
  2. HGAM_biomass: All fits of HGAMs for biomass  
    2.1 bio_position_family_I.RData: Fit of HGAM for family biomass different similar group-level trends  
  2.2 bio_position_family_S.RData: Fit of HGAM for family biomass with similar group-level trends  
  2.3 bio_position_order_I.RData: Fit of HGAM for order biomass different similar group-level trends    
  2.4 bio_position_order_I.RData: Fit of HGAM for order biomass different similar group-level trends    
  2.5 bio_position_order_S.RData: Fit of HGAM for order biomass with similar group-level trends  
  2.6 bio_position_S.RData: Fit of HGAM for total biomass with similar group-level trends  
  
   3. stats_biomass_abundance_data: all biomass and abundance data  
  3.1 biomass_emergence_family_sample.csv: Biomass and abundance of emergent aquatic insect families per sample  
  3.2 biomass_emergence_order_sample.csv: Biomass and abundance of emergent aquatic insect orders per sample  
  3.3 biomass_emergence_sample.csv: Biomass and abundance of emergent aquatic insects per sample  
  
 4. stats_land_use_related_drivers_data: all land-use-realated drivers  
  4.1 data_env_1.csv: Land-use-related drivers of emergent aquatic insects
 
 5. stats_trait_data: All trait data  
  5.1 trait_data.csv: Traits generation time and size of emergent aquatic insects  
  5.2 trait_data_diff.csv: Difference trait data between forested and agricultural sites 
