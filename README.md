---
editor_options: 
  markdown: 
    wrap: 72
---

# ML_Group_Project

Git Hub Repository for the Machine Learning group project.

**1. Introduction**

In this section, describe what you are planning to do. Also, briefly
describe related work.

When discussing related work, do not forget to include appropriate
references. This is an example of a citation
\cite{kim_convolutional_2014}. To format the citations properly, put the
corresponding references into the bibliography.bib file. You can obtain
BibTeX-formatted references for the "bib" file from Google Scholar
(\url{https://scholar.google.com}), for example, by clicking on the
double-quote character under a citation and then selecting,
\mbox{"BibTeX"} as shown in Figure \ref{fig:google-scholar-1col} and
Figure \ref{fig:google-scholar-2col}.

------------------------------------------------------------------------

The three of us are really interested in current health policies and we
found some interesting datasets regarding abortion numbers on the
state-level within Germany. We believe that based on this data, we can
contribute to finding answers regarding cross country abortion travel.
Especially within the Schengen Area, citizens of countries with (more)
restrictive abortion policies might travel across borders to receive
abortion treatment in (more) permissive neighboring states. Abortion
policies of one country would thereby have an influence on abortion
numbers in neighboring countries as well. We intend to shine a light on
such effects by looking at data for the German states: Given for
instance the strict regulation of abortions in Poland, a possible
finding in line with the described assumption could be higher numbers of
abortions performed on foreigners in German states close by Polish
border. Quantifying such cross-border effects could as well help
assessing the effectiveness of Schengen countries´ attempts to keep
control over their abortion policies.

Dependent Variable: Share of Abortions performed on foreigners on
overall population per state in proportion to: Share of foreign
population on overall population per state

Independent Variables:

- Proximity of neighboring countries (geographical distance)
- Including restrictiveness of respective countries (using abortion atlas scores)
- Foreign population per state (share of overall population)
- Including restrictiveness of respective countries (using abortion atlas scores)
- Interesting to estimate effect of foreigners permanently living in the state vs. people temporarily migrating for the abortion
- Maybe even negative effect? People like going to their country of origin for their abortion?
- Interesting for network effects (foreigners going for their abortion to states where they have relatives/social network)
- If feasible/possible: Control for share of female between 12-50 years
- Population with a migrant background per state (no fitting data found yet)
- Including restrictiveness of respective countries (using abortion atlas scores)
- Interesting for network effects (foreigners going for their abortion to states where they have relatives/social network)

Research questions:
- Is there a over-proportionally big share of
abortions performed on foreigeners in some states?
- Classification
approach: Is a given abortion (based on the input data/independent
variables) predicted to be classified by our model to be performed on a
foreigner or a German?
- Binary classification: foreigner/German
abortion

Model used: SGD Classifier (TBA)


**2. Motivation**

Describe why your project is interesting. E.g., you can describe why
your project could have a broader societal im- pact. Or, you may
describe the motivation from a personal learning perspective.

|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------|
| "Here we should talk about the state of abortion policy in europe in the last couple of years, and see the state of it currently (could use information from the Atlas")

**Societal Relevance**:

Europe's health systems are embedded in their respective social welfare landscapes. However, this also means that health systems in the EU are diverse and reflect different social choices. On the other hand, health systems in the EU are increasingly interacting with each other. Especially since the Directive on Patients' Rights in Cross-Border Healthcare. (Richtlinie 2011/24/EU über die Ausübung der Patientenrechte in der grenzüberschreitenden Gesundheitsversorgung (ABl. L 88 vom 4.4.2011). For patients in Europe, this means that the costs for treatment abroad are reimbursed by the respective health insurance fund up to the amount that would have been incurred for the corresponding treatment at home.

In keeping with this vision, we believe that our project could contribute to improving access to safe and legal abortion care throughout Europe. Cross-border patient movements are a fact of our time. With our model, countries could better prepare themselves for this fact. Social actors could anticipat and estimat effects of stricter policies in neighboring countries on their own healthcare system. Governments have a responsibility to safeguard the right of women and girls to lead free and safe reproductive lives without discrimination and coercion.

**Research relevance**:

The Europe Abortion Access Project writes on its research website that the phenomenon of transnational abortion travel remains poorly understood. According to them, this requires further quantitative and qualitative studies. They write that it is known that many European women travel for abortions outside and/or within the borders of their country of residence, even from countries with relatively liberal abortion laws. (accessed on October 5 2022, section "journeys": <https://europeabortionaccessproject.org/#what>)

- project developed in German context could be systematically expanded to include data from more (future) years, expand to more European countries, create model to estimate of cross-country abortion travel within the European Union and estimate for example the impact of a changing national legislation as reflected in the abortion atlas

**possible real world use**:

- Morality policies as a core of polity´s self-definition (look up source). If Schengen allows to bypass national regulation of abortion policies via cross-country abortion travel, that would undermine the effectiveness of national regulation on the issue beyond self-attribution(?) (needs revision, too strongly put)                                                                                                                                    
**Learning perspective**:

- big data set (ca. 100.000 abortions in Germany per year), combining different data sets, distinction of abortion on German/abortion on foreigner allows to explore a classification model
- interest in Health policies, first step in applying ML knowledge to policy analysis in this field
- combining different types of data sources, practicing how to handle different tyoes of data sources:
- policy atlas to be read out
- big data sets/ census and abortion data
- creation of distance/geographic variables
- getting an impression on how well data sources from European multi-level governance system (in this case: state, country, EU) can be combined in order to gain insights                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     

**3. Evaluation**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              

What would the successful outcome of your project look like? In other words, under which circumstances would you consider your project to be 'successful'? How do you measure success, specific to this project, from a technical standpoint?

------------------------------------------------------------------------

Our Research model aims to shine a light on the question if the proximity of German states to bordering nations with a more restrictive stance on abortion leads to a higher percentage of abortions performed on foreigners in these states. Therefore, our Classification approach would be successful if we can predict if a given abortion, based on the input data/independent variables, was performed on a foreigner or a German. For [classification predictions](<https://www.jeremyjordan.me/evaluating-a-machine-learning-model/#:~:text=The%20three%20main%20metrics%20used,the%20number%20of%20total%20predictions.>), there are four possible types of outcomes: true positives, true negatives, false positives, false negatives. With this outcomes we can evaluate our classification model by its accuracy, precision, and recall. The most important evaluation metrics are precision (true positives / all positives) and recall (true positives / (false negatives + true positives)). For our initial research question, it will be more important to obtain a higher precision score, since we will be looking to develop a ML model that can accurately predict if an abortion procedure realized on German territory was applied to a German citizen or a foreigner.

 **4. Resources** 
 
What resources are you going to use (datasets, computer hardware, computational tools, etc.)?       

------------------------------------------------------------------------

| Data Sets 
1. The [European Abortion Policies Atlas-September 2021](<https://www.epfweb.org/node/857>) - "scores 53 European countries and territories on legal frameworks to access safe abortion care" (from epf website) - "This initiative is powered by the European Parliamentary Forum for Sexual and Reproductive Rights (EPF) and International Planned Parenthood Federation European Network (IPPF EN). We are grateful to the numerous national organisations and country experts who contributed to gathering the data presented in the Atlas. The Atlas was produced in partnership with a group of experts in sexual and reproductive health and rights (see overleaf ) who designed the questions and structures. The scope and the content of the European Contraception Atlas is the sole responsibility of EPF and IPPF EN." (from Atlas PDF itself) - "EXPERT GROUP: The below group of experts in sexual and reproductive health and rights designed the questions and structures for the Atlas. - LEGAL: Sylvie Lausberg / Diane Gardiol, Centre d'Action Laïque ASBL, Aintzane Marquéz, Women's Link Worldwide - MEDICAL: Marge Berer, International Campaign for Women's Right to Safe Abortion - ACADEMIA: Niklas Barke, Åbo Akademi University - POLITICIANS: Hon. Lia Quartapelle, MP (Italy) - PRACTITIONER: Yannick Manigart, OBGYN, University Hospital CHU Saint Pierre - INTERNATIONAL STANDARDS: Antonella Lavelanet, WHO - YOUTH: Lili Steffen, Y Safe - PROJECT PARTNERS: Neil Datta / Marina Davidashvili, EPF, Caroline Hickson / Irene Donadio / Lena Luyckfasseel, IPPF EN" (from Atlas PDF itself) - an overall score on a scale from 0-100 composed of four sections with several sub-categories: - "ACCESS", - "LEGAL STATUS OF ABORTION CARE", - "CLINICAL CARE AND SERVICE DELIVERY", - "INFORMATION AND ON-LINE INFORMATION" - contains information from September 2021. 
2. [Abortion Statistics for Germany: Genesis (statistisches Bundesamt) ID: 23311-0006](<https://www-genesis.destatis.de/genesis//online?operation=table&code=23311-0006&bypass=true&levelindex=1&levelid=1664961110565#abreadcrumb>) - contains state level information on abortions performed on a annual base (also available by quartal), including (among others) information about the origin of the receiving patient distinguishing between the different states of Germany and category "Foreigner" - contains information for all 16 states with an annual number of about 100.000 abortions performed in Germany.
3. [Foreign population: Ausländer: Bundesländer, Stichtag, Geschlecht, Altersjahre, Ländergruppierungen/Staatsangehörigkeit. Genesis (statistisches Bundesamt) ID: 12521-0022](<https://www-genesis.destatis.de/genesis/online#astructure>) - contains (among others) annual information on the share and composition of foreigners among the population of each German state.
4. [World Cities Database](https://simplemaps.com/data/world-cities): With the help of this database, which contains information like City Name, Longitude, Latitude, Country, State, Region, City Status, Population Density, Population, and Id of more than 4 million unique cities around de world, we will create our own database with the information needed for the European Continent. With this databse we expect to calculate the shortest distance from all of the German State's Capitals (or their biggest city) with the closest city from their neighbouring european countries, in order to determine the distance between said states and countries.
5. [Abortion statistics](https://www-genesis.destatis.de/) published by the Federal Statistical Office of Germany contain numbers for annual abortions in each state, distinguishing (among others) between abortions performed on foreigners and native population. The European Parliamentary Forum for Sexual and Reproductive Rights developed the [European Abortion Policies Atlas](https://www.epfweb.org/sites/default/files/2021-09/ABORT%20Atlas_EN%202021-v5.pdf), which is an in-depth analysis of abortion policies across Europe. Within their atlas, European countries are ranked based on their policies regarding abortion and abortion care. Combining this data with [German census data](https://www-genesis.destatis.de/genesis/online?operation=table&code=12521-0021&bypass=true&levelindex=0&levelid=1664271586875#abreadcrumb), we hope to identify driving factors for higher shares of abortions performed on foreigners, checking for variables such as composition of foreign population or proximity to neighboring countries with stricter abortion policies.

|Computational tools 
Github will be used for version control and collaboration, and coding will be performed in Jupyter Notebooks and Visual Studio Code.

**5. Contributions**

You are expected to share the workload evenly, and every group member is
expected to participate in both the experiments and writing. (As a
group, you only need to submit one proposal and one report, though. So
you need to work together and coordinate your efforts.)

Clearly indicate what computational and writing task each member of your
group will be participating in.

*|Sections required on final project:
0. Abstract 
1. Introduction
2. Related Work (Alvaro)
3. Proposed Method 
5. Analysis 
6. Conclusions 
7. Acknowledgements 
8. Contributions (Alvaro) 
9. References (all) 
10. Appendix (all) 

------------------------------------------------------------------------

Group member Alvaro Guijarro will be primarely focused on the data wrangling and preprocessing section in the Machile Learning pipeline. In order to costruct an effective ML classification model, we must work with a robust and clean data set, which will be the result of combining different data sources into a unified dataframe. Once this is done, we can later confidently split our data into the necessary training and testing sets. Alongside this tasks, Alvaro will also be leading the "Related Work", "Experiments" and "Contributions" sections of the final project report. 
Nevertheless, all team members are expected to support and contribute towards the development of the ML model and writing of the final project paper.  
