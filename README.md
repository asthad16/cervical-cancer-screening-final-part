# cervical-cancer-screening-final-part
After analyzing attributes obtained from feature importance, nine new dependent variables are added in the dataset.
Feature Extraction
     Analysis done from the feature correlation and selection, identified the seven most important attributes that have strong relation with the target variable(biopsy) including Age of the person, when first sexual act happened, total number of pregnancies, partners with whom person was sexually active, Smokes, Hormonal Contraceptives and IUD. Using these features nine new features are obtained by applying below described equations.
     YRSS (Years passed since patient had first sexual act) = Age – time of first sexual activity of the person

NSPP (Number of partners with whom sexually active since first time as a percentage) = Number of partners/ YRSS

HPA = Years of the use of hormonal contraceptives/ Age

TPS (Total packets of cigarettes smoked) = Smokes (packs/year) * Smokes (years)

NPA = Number of times pregnant / Age

NSA = Number of partners with whom sexually active / Age

NYHC (Number of years patient did not take Hormonal Contraceptives) = Age – Years of use of hormonal contraceptives

APP = Number of times pregnant / Number of partners with whom sexually active

NHCP (number of years patient took Hormonal Contraceptives after first sexual act as a percentage''') = Hormonal Contraceptives (years) / YRSS

