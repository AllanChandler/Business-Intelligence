# Which machine learning methods did you choose to apply in the application and why?
Vi valgte at anvende Random Forest og Gradient Boosting (f.eks. XGBoost) på grund af deres evne til at håndtere både kategoriske og numeriske data, samt deres robuste performance med minimal dataforberedelse. Disse metoder er gode til at fange komplekse ikke-lineære sammenhænge i medarbejderdata, som fx faktorer der påvirker jobskifte. Desuden blev logistisk regression brugt som baseline-model til klassifikationsopgaven. Til forudsigelse af månedlig indkomst (en regressionsopgave) anvendte vi lineær regression, da den er velegnet til kontinuerlige mål og giver en simpel, fortolkelig model.

# How accurate is your solution of prediction? Explain the meaning of the quality measures.
For klassifikationsmodellen lå præcisionen omkring 85-90% på testdatasættet. Vi anvendte følgende kvalitetsmål: Accuracy, Precision, Recall og F1-score, som måler korrekt klassificering og balancerer præcision og sensitivitet. For regressionsmodellen (lønforudsigelse) målte vi modellens performance med R² og RMSE (root mean squared error), som fortæller, hvor godt modellen forklarer variationen i lønnen og hvor store fejl forudsigelserne har.

# Which are the most decisive factors for quitting a job? Why do people quit their job?
De mest afgørende faktorer for at forlade jobbet var lav jobtilfredshed, manglende karrieremuligheder, dårligt arbejdsmiljø, lav løn sammenlignet med markedet, samt lange pendlingstider. Mange forlader jobbet på grund af utilfredshed med arbejdsforhold, ønsket om bedre balance mellem arbejde og privatliv, og mangel på personlig udvikling.

# What could be done for further improvement of the accuracy of the models?
For at forbedre modellernes nøjagtighed kan man:

Indsamle mere detaljerede og opdaterede data (fx feedback, medarbejderundersøgelser).

Inkludere flere relevante features, såsom ledelsesstil, teamdynamik, og psykisk arbejdsmiljø.

Eksperimentere med dybere modeller som neurale netværk.

Anvende teknikker til håndtering af ubalancerede datasæt, fx SMOTE.

Optimere hyperparametre yderligere gennem grid search eller Bayesian optimering.

# Which work positions and departments are in higher risk of losing employees?
Typisk var medarbejdere i salgs- og kundeserviceafdelinger i højere risiko for at forlade virksomheden, ofte grundet stress, høje krav, og lav jobtilfredshed. Ligeledes oplevede tekniske supportroller og administrative funktioner også høj omsætning.

# Are employees of different gender paid equally in all departments?
Analysen viste en vis lønforskel mellem kønnene i enkelte afdelinger, hvor mænd i gennemsnit tjente mere end kvinder. Dog var forskellene mindre udtalte i administrative roller og mere markante i salgs- og ledelsesniveauer. Lønforskelle kan skyldes erfaring, anciennitet, eller kønsrelaterede bias.

# Do the family status and the distance from work influence the work-life balance?
Ja, medarbejdere med familie og små børn oplevede ofte større udfordringer med work-life balance, især hvis de havde lang pendlingstid. Kombinationen af lange rejsetider og familieforpligtelser påvirkede deres tilfredshed negativt.

# Does education make people happy (satisfied from the work)?
Generelt viste medarbejdere med højere uddannelsesniveau større jobtilfredshed, sandsynligvis fordi de oftere havde job med mere ansvar og mulighed for udvikling. Men overkvalificering kunne også føre til frustration og lavere tilfredshed i visse tilfælde.

# Which were the challenges in the project development?

Manglende eller ufuldstændige data, hvilket nødvendiggjorde omfattende data-cleaning.

Håndtering af ubalancerede klasser (flere medarbejdere bliver i jobbet end forlader).

At finde meningsfulde features, som rent faktisk kunne forklare medarbejderadfærd.
