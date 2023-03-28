# Database_biomed <br />
Synthetic Biomedical Science database <br />
This database was created to support data handling, analysis and display. <br />

## To load/import the data into RStudio:  <br />
url <- "https://raw.githubusercontent.com/m-dimiceli/Database_biomed/Databases/UoW_biomed_v2.csv?token=GHSAT0AAAAAACAV7IVWQYXDHB27QKMRSJ4AZBC7P5A" <br />
data <- read.csv(url) <br />

## To load/import data features (this document) into RStudio:  <br />
url2 <- "https://raw.githubusercontent.com/m-dimiceli/Database_biomed/Databases/README.md?token=GHSAT0AAAAAACAV7MDQP6WRPYZFZ6HEJ4AIZBDAZAA" <br />
url2 <br />
features <- readLines(url2) <br />
features <br />

## Database description: <br />
Size: 108 KB <br />
Entries: 600 observations of 26 variables <br />
Format: .csv document (comma-separated values) <br />
Simulation: biomedical science <br />

## Abbreviations: <br />
chr: character <br />
int: integer <br />
num: numeric <br />
dp: decimal point(s) <br />

## Variables: <br />
ID: chr, participant assigned hexadecimal identification, [A-Z][0000-9999][A-Z]. <br />
job: chr, job. <br />
car_col: chr, car colour, 2 factors 'Black' or 'Other'. <br />
car_pwr: num, car power, 2 dp. <br />
chromo: chr, sex chromosome, 2 factors 'XX' or 'XY'. <br />
eye_col: chr, eye colour, 7 factors 'brown', 'hazel', 'blue', 'green', 'gray', 'amber', 'rare'. <br />
CT_drug: chr, clinical trial drug group, 2 factors 'placebo' or 'heparin' <br />
age: int, age, in years. <br />
IQ: int, intellectual quotient. <br />
height: num, height, 1 dp, in cm. <br />
weight: int, weight, in Kg. <br />
foot_len: num, dominant foot length, 1 dp, in cm. <br />
D4_len: num, dominant hand 4th digit length, 1 dp, in mm. <br />
hand_len: num, dominant hand length, 1 dp, in cm. <br />
tot_RBC: numt, total red blood cells count, 1 dp, in 10^9/ml. <br />
tot_plat: num, total platelets count, 1 dp, in 10^9/ml. <br />
tot_WC: num, total white cells count, 1 dp, in 10^9/ml. <br />
tot_mono: num, total monocytes count, 3 dp, in 10^9/ml. <br />
tot_lympho: num, total lymphocytes count, 2 dp, in 10^9/ml. <br />
tot_eosi: num, total eosinophiles count, 2 dp, in 10^9/ml. <br />
hematocr: num, hematocrit ratio, 3 dp. <br />
det_CRP: int, 2 factors '0' or '1'. <br />
s_cort: num, serum cortisol level, 2 dp, in mg/l. <br />
s_b12: num, serum vitamin B12 level, 2 dp, in pmol/l. <br />
BP_dia: int, diastolic blood pressure, in mmHg. <br />
BP_syst: int, systolic blood pressure, in mmHg. <br />

## Licence:  <br />
Fully open <br />
m.dimiceli@worc.ac.uk <br />

## Versions: <br />
v2: 28/March/2023 <br />
