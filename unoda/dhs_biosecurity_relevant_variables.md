# DHS Individual Recode: Biosecurity-related Main Variable Menu

- Your analysis should include at least one of these variables, ideally as the main outcome or primary dependent variable. 

- It intentionally excludes general demographic and socioeconomic variables such as education, literacy, wealth, age, region, and urban/rural residence. 
Students can still use those as explanatory variables.

- Not all variables are available in all DHS surveys. Availability depends on survey year, country, questionnaire modules, DHS phase, and whether a given module was fielded.

---


## WASH, Hygiene, and Household Infection Prevention

| Level | Code | Variable meaning |
|---|---|---|
| Woman/Household | `V113` | Source of drinking water |
| Woman/Household | `V115` | Time to collect drinking water |
| Woman/Household | `V116` | Type of toilet facility |
| Woman/Household | `V160` | Toilet shared with other households |
| Woman | `V462` | Washed hands before preparing last meal |
| Woman | `V465` | Disposal of youngest child's stools |

---

## Tuberculosis Knowledge, Transmission, and Stigma

| Level | Code | Variable meaning |
|---|---|---|
| Woman | `V474` | Heard of tuberculosis (TB) |
| Woman | `V474A` | Knows TB spreads through air when coughing/sneezing |
| Woman | `V474B` | Believes TB spreads by sharing utensils |
| Woman | `V474C` | Believes TB spreads by touching a person with TB |
| Woman | `V474D` | Believes TB spreads through food |
| Woman | `V474E` | Believes TB spreads through sexual contact |
| Woman | `V474F` | Believes TB spreads through mosquito bites |
| Woman | `V474Z` | Does not know how TB spreads |
| Woman | `V475` | Believes TB can be cured |
| Woman | `V476` | Would keep it secret if a family member had TB |

---

## Injection Safety and Infection Prevention

| Level | Code | Variable meaning |
|---|---|---|
| Woman | `V477` | Number of injections received in last 12 months |
| Woman | `V478` | Injections administered by a health worker |
| Woman | `V479` | Source/provider of injection |
| Woman | `V480` | Syringe/needle came from a new unopened package |

---

## HIV, AIDS, STI, Testing, and Prevention

| Level | Code | Variable meaning |
|---|---|---|
| Woman | `V750` | Heard of AIDS or sexually transmitted infections |
| Woman | `V751` | Ever heard of AIDS |
| Woman | `V754CP` | Knows condom use reduces HIV risk |
| Woman | `V754DP` | Knows having one uninfected partner reduces HIV risk |
| Woman | `V754JP` | Believes HIV can be transmitted by mosquito bites |
| Woman | `V754WP` | Believes HIV can be transmitted through sharing food |
| Woman | `V756` | Knows a healthy-looking person can have HIV |
| Woman | `V761` | Used condom at last intercourse |
| Woman | `V763A` | Had an STI in last 12 months |
| Woman | `V763B` | Had genital sore/ulcer in last 12 months |
| Woman | `V763C` | Had genital discharge in last 12 months |
| Woman | `V770` | Sought advice or treatment for STI |
| Woman | `V774A` | Knows HIV can be transmitted during pregnancy |
| Woman | `V774B` | Knows HIV can be transmitted during delivery |
| Woman | `V774C` | Knows HIV can be transmitted through breastfeeding |
| Woman | `V781` | Ever tested for HIV |
| Woman | `V783` | Knows a place to obtain an HIV test |
| Woman | `V785` | Heard about STIs |
| Woman | `V822` | Justified asking partner to use condom if STI present |
| Woman | `V824` | Knows drugs can reduce mother-to-child HIV transmission |
| Woman | `V826A` | Time since most recent HIV test |
| Woman | `V828` | Received results of most recent HIV test |
| Woman | `V839` | Offered HIV test during antenatal care |
| Woman | `V840` | Tested for HIV during antenatal care |
| Woman | `V841` | Received HIV test results from antenatal care |
| Woman | `V843` | Tested for HIV after antenatal-related testing |
| Woman | `V855` | Received post-test HIV counseling |
| Woman | `V856` | Knowledge/use of HIV self-test kits |
| Woman | `V857A` | Attitudes toward children with HIV attending school |
| Woman | `V857B` | Perceived fear of HIV testing due to social reactions |
| Woman | `V857C` | Perceived HIV-related stigma |
| Woman | `V857D` | Perceived loss of respect associated with HIV |
| Woman | `V858` | Fear of HIV transmission through saliva contact |

---

## Health-System Access and Care-Seeking

| Level | Code | Variable meaning |
|---|---|---|
| Woman | `V467A` | Problem knowing where to seek treatment |
| Woman | `V467B` | Problem obtaining permission for treatment |
| Woman | `V467C` | Problem obtaining money for treatment |
| Woman | `V467D` | Distance to facility is a problem |
| Woman | `V467E` | Transportation is a problem |
| Woman | `V467F` | Not wanting to go alone |
| Woman | `V467G` | Concern no female provider available |
| Woman | `V467H` | Concern no provider available |
| Woman | `V467I` | Concern no medicines available |

---

## Child Illness, Symptoms, and Diagnostic Testing

**Note:** Child variables are stored as repeated child records in IR and may require reshaping.

| Level | Code | Variable meaning |
|---|---|---|
| Child | `H11` | Diarrhea |
| Child | `H11B` | Blood in stool during diarrhea |
| Child | `H22` | Fever in last two weeks |
| Child | `H31` | Cough in last two weeks |
| Child | `H31B` | Rapid breathing |
| Child | `H31C` | Chest-related breathing difficulty |
| Child | `H44C` | Diarrhea still ongoing |
| Child | `H47` | Blood taken for diagnostic testing after fever |

---

## Child Treatment and Care-Seeking

**Note:** Child variables are stored as repeated child records in IR and may require reshaping.

| Level | Code | Variable meaning |
|---|---|---|
| Child | `H12Y` | No advice/treatment sought for diarrhea |
| Child | `H12Z` | Taken to facility for diarrhea treatment |
| Child | `H13` | Received ORS |
| Child | `H13B` | Received packaged ORS liquid |
| Child | `H14` | Received home rehydration solution |
| Child | `H15` | Received oral antibiotics |
| Child | `H15B` | Received injectable antibiotics |
| Child | `H15C` | Received IV fluids |
| Child | `H15E` | Received zinc |
| Child | `H20` | Received other treatment |
| Child | `H21` | Any treatment/advice sought |
| Child | `H38` | Amount offered to drink during diarrhea |
| Child | `H39` | Amount offered to eat during diarrhea |
| Child | `H43` | Received deworming medication |
| Child | `H44A` | First place treatment sought |
| Child | `H44B` | Delay before treatment sought |
| Child | `H32Y` | No advice/treatment sought for fever/cough |
| Child | `H32Z` | Taken to facility for fever/cough |
| Child | `H46A` | First place treatment sought for fever |
| Child | `H46B` | Delay before treatment sought for fever |

---

## Child Vaccination and Immunization

**Note:** Child variables are stored as repeated child records in IR and may require reshaping.

| Level | Code | Variable meaning |
|---|---|---|
| Child | `H1` | Vaccination card available/seen |
| Child | `H10` | Ever received any vaccination |
| Child | `H2` | BCG vaccination |
| Child | `H3` | DPT1 vaccination |
| Child | `H5` | DPT2 vaccination |
| Child | `H7` | DPT3 vaccination |
| Child | `H4` | Polio1 vaccination |
| Child | `H6` | Polio2 vaccination |
| Child | `H8` | Polio3 vaccination |
| Child | `H9` | Measles vaccination |
| Child | `H9A` | Second measles vaccination |
| Child | `H0` | Polio birth dose |
| Child | `H35` | Vaccinated during campaign/NID |
| Child | `H50` | Hepatitis B birth dose |
| Child | `H51` | Pentavalent 1 |
| Child | `H52` | Pentavalent 2 |
| Child | `H53` | Pentavalent 3 |
| Child | `H54` | Pneumococcal 1 |
| Child | `H55` | Pneumococcal 2 |
| Child | `H56` | Pneumococcal 3 |
| Child | `H57` | Rotavirus 1 |
| Child | `H58` | Rotavirus 2 |
| Child | `H59` | Rotavirus 3 |
| Child | `H60` | Inactivated polio vaccine |
| Child | `H64` | Hib 1 |
| Child | `H65` | Hib 2 |
| Child | `H66` | Hib 3 |


- `V480` — Safe injection practice
- `V781` — Ever tested for HIV
- `V828` — Received HIV test results
- `V763A` — STI in last 12 months
- `V770` — Sought treatment for STI
