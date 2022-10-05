# ML_Group_Project
Git Hub Repository for the Machine Learning group project.

**1. Introduction**

In this section, describe what you are planning to do. Also, briefly describe related work.

When discussing related work, do not forget to include appropriate references.  This is an example of a citation \cite{kim_convolutional_2014}. To format the citations properly, put the corresponding references into the bibliography.bib file. You can obtain BibTeX-formatted references for the "bib" file from Google Scholar (\url{https://scholar.google.com}), for example, by clicking on the double-quote character under a citation and then selecting, \mbox{"BibTeX"} as shown in Figure \ref{fig:google-scholar-1col} and Figure \ref{fig:google-scholar-2col}.

-----

The three of us are really interested in current health policies and we found some interesting datasets regarding abortion numbers on the state-level within Germany. We believe that based on this data, we can contribute to finding answers regarding cross country abortion travel. Especially within the Schengen Area, citizens of countries with (more) restrictive abortion policies might travel across borders to receive abortion treatment in (more) permissive neighboring states. Abortion policies of one country would thereby have an influence on abortion numbers in neighboring countries as well. We intend to shine a light on such effects by looking at data for the German states: Given for instance the strict regulation of abortions in Poland, a possible finding in line with the described assumption could be higher numbers of abortions performed on foreigners in German states close by Polish border. Quantifying such cross-border effects could as well help assessing the effectiveness of Schengen countries´ attempts to keep control over their abortion policies.

**2. Motivation**

Describe why your project is interesting. E.g., you can
describe why your project could have a broader societal im-
pact. Or, you may describe the motivation from a personal
learning perspective.

-----
"Here we should talk about the state of abortion policy in europe in the last couple of years, and see the state of it currently (could use information from the Atlas")

societal relevance:
- "Europe Abortion Access Project" argues that their project aims to "improve access to safe and legal abortion care throughout Europe. Since we work on a related topic, we can argue the same
- Foret and Calligaro (2018): "European Values. Challenges and Opportunities for EU Governance" discuss relevance of morality policies "in the institutionalization of the EU as a political order" (from abstract, check on-campus access: https://www.taylorfrancis.com/books/edit/10.4324/9781351037426/european-values-fran%C3%A7ois-foret-oriane-calligaro?refId=61de8daf-e9a8-4437-b02d-adbee4545556&context=ubx)
- Morality policies as a core of polity´s self-definition (look up source). If Schengen allows to bypass national regulation of abortion policies via cross-country abortion travel, that would undermine the effectiveness of national regulation on the issue beyond self-attribution(?) (needs revision, too strongly put)


research relevance:
- "Europe Abortion Access Project" states on their research website that the "phenomenon [of cross-country abortion travel] remains poorly understood" and needs for further quantitative and qualitative study:
"Many European women are known to travel to seek abortions outside and/or within the borders of their country of residency, including from countries with relatively liberal abortion laws, which are the main focus of this study. As this phenomenon remains poorly understood, this research project makes a conscious effort to unravel the complex reasons behind decisions to travel in order to obtain abortion care, by exploring women’s experiences when travelling to seek treatment. Data collected annually by the Department of Health of England and Wales (2017) indicate that 4810 abortions were performed for non-residents in the UK in 2016. We learned from our 2014-2015 pilot study that women from 14 countries came to the UK to seek abortion care, with Italian and French women representing the most numerous groups (Gerdts et al 2016). Data from the Netherlands (Rutgers, 2016) similarly show that almost 3000 women travelled there to seek abortion care in 2014, mainly from France, Germany and Belgium. Further quantitative and qualitative data are needed to fully understand the experiences of women who travel to seek abortion care within Europe."
(accessed on October 5 2022, section "journeys": https://europeabortionaccessproject.org/#what)
- project developed in German context could be systematically expanded to include data from more (future) years, expand to more European countries, create model to estimate of cross-country abortion travel within the European Union and estimate for example the impact of a changing national legislation as reflected in the abortion atlas 

learning perspective:
- big data set (ca. 100.000 abortions in Germany per year), combining different data sets, distinction of abortion on German/abortion on foreigner allows to explore a classification model
- interest in Health policies, first step in applying ML knowledge to policy analysis in this field
- combining different types of data sources, practicing how to handle different tyoes of data sources:
    - policy atlas to be read out
    - big data sets/ census and abortion data
    - creation of distance/geographic variables
- getting an impression on how well data sources from European multi-level governance system (in this case: state, country, EU) can be combined in order to gain insights

**3. Evaluation**

What would the successful outcome of your project look
like? In other words, under which circumstances would you
consider your project to be ‘successful’?
How do you measure success, specific to this project,
from a technical standpoint?

**4. Resources**

What resources are you going to use (datasets, computer hardware, computational tools, etc.)?

Data Sets
1. The European Abortion Policies Atlas-September 2021 (https://www.epfweb.org/node/857)
2. Abortion Statistics for Germany: Genesis (statistisches Bundesamt) ID: 23311-0006
(https://www-genesis.destatis.de/genesis//online?operation=table&code=23311-0006&bypass=true&levelindex=1&levelid=1664961110565#abreadcrumb)
3. Foreign population: Ausländer: Bundesländer, Stichtag, Geschlecht, Altersjahre,
Ländergruppierungen/Staatsangehörigkeit. Genesis (statistisches Bundesamt) ID: 12521-0022 (https://www-genesis.destatis.de/genesis/online#astructure)

-----

[Abortion statistics](https://www-genesis.destatis.de/) published by the Federal Statistical Office of Germany contain numbers for annual abortions in each state, distinguishing (among others) between abortions performed on foreigners and native population. The European Parliamentary Forum for Sexual and Reproductive Rights developed the [European Abortion Policies Atlas](https://www.epfweb.org/sites/default/files/2021-09/ABORT%20Atlas_EN%202021-v5.pdf), which is an in-depth analysis of abortion policies across Europe. Within their atlas, European countries are ranked based on their policies regarding abortion and abortion care.  Combining this data with [German census data](https://www-genesis.destatis.de/genesis/online?operation=table&code=12521-0021&bypass=true&levelindex=0&levelid=1664271586875#abreadcrumb), we hope to identify driving factors for higher shares of abortions performed on foreigners, checking for variables such as composition of foreign population or proximity to neighboring countries with stricter abortion policies.

**5. Contributions**

You are expected to share the workload evenly, and every group member is expected to participate in both the experiments and writing. (As a group, you only need to submit one proposal and one report, though. So you need to work together and coordinate your efforts.)

Clearly indicate what computational and writing task each member of your group will be participating in.
