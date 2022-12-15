| **End of OxCGRT data collection, December 2022** |
| --- |
| The Oxford COVID-19 Government Response Tracker will stop publishing real-time updates for most jurisdictions at the end of 2022. Reviewing and confirming data will continue into 2023. Most governments around the world have settled into a steady state of pandemic-related policy – there are not many significant changes for us to report. </br></br>At this stage, we are planning to continue publishing data for individual Chinese provinces into 2023, as there is still significant policy variation and change. We will publish a separate repository for this soon. </br></br>We have posted a longer update on the [Blavatnik School of Government website](https://www.bsg.ox.ac.uk/future-oxford-covid-19-government-response-tracker). The OxCGRT dataset will continue to be available, primarily on this GitHub repository, and we will establish a lasting internet presence over the course of 2023. Our main channel for updates will be our data users mailing list, which you can join here: http://eepurl.com/hiMsdL |

# USA state level Covid-19 Policy Responses
Systematic dataset of USA sub-national Covid-19 policy data

**NOTE:** for US state data that is directly comparable with our country-level data, please visit our [OxCGRT/covid-policy-tracker](https://github.com/OxCGRT/covid-policy-tracker) repository.

This is a project from the [Blavatnik School of Government](https://www.bsg.ox.ac.uk), drawing on the [Blavatnik School of Government OxCGRT](https://www.bsg.ox.ac.uk/covidtracker).

More information is available on the project's website: [https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker](https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker).

---

__Cite as:__ Laura Hallas, Ariq Hatibie, Saptarshi Majumdar, Monika Pyarali, Rachelle Koch, Andrew Wood and Thomas Hale (2020). [_Variation in US states’ responses to COVID-19_3.0_] (https://www.bsg.ox.ac.uk/research/publications/variation-us-states-responses-covid-19). Blavatnik School of Government.

---

### Dataset of USA sub-national Covid-19 government response policies

Drawing on the Oxford COVID-19 Government Response Tracker (OxCGRT) [coding system](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md), we provide a systematic and objective account of the strength of Covid-19 response policies that have been instigated by the USA’s national government, state governments, and governments of Washington DC and the US Virgin Islands. Currently we provide coding up to 31 July 2020 for 13 indicators: C1 through C8, E1, E2, and H1 through H3. These indicators allow the creation of four different [indices](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/index_methodology.md): the stringency index, the containment and health index, the economic support index, and the government response index.

The US state data has been incorporated into the primary [OxCGRT/covid-policy-tracker](https://github.com/OxCGRT/covid-policy-tracker) repository. This repository contains **a secondary dataset that cannot be interpreted alongside our primary country data**, but may be of interest nonetheless. The differences are described below.

The [subnational documentation](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/subnational_interpretation.md) on our primary [OxCGRT/covid-policy-tracker](https://github.com/OxCGRT/covid-policy-tracker) repository contains more information about how to interpret subnational data.

### Differences from primary OxCGRT data 

This repo contains data for two levels of policies, described using the suffixes of "GOV" and "WIDE." Policies described with the suffix "GOV" refers to policies issued by a specific level of government, and can be used to compare government responses across different levels of government. Policies with the suffix "WIDE" describe all government responses taken by a specific jurisdiction and those below it, but do not include policy decisions taken by higher-level jurisdictions. The USA subnational repo contains two descriptive labels:
- NAT_GOV: Policies issued by the USA federal government only.
- STATE_WIDE: Policies issued by state governments and by sub-state governments.

For this repo's STATE_WIDE distinction, the "WIDE" suffix observations do not incorporate policies from higher levels of government that may supercede local policies. For example, if a country has an international travel restriction that applies country-wide, this would appear as a NAT_GOV policy and not within STATE_WIDE.

Note that STATE_WIDE observations at the subnational level, which code the totality of policies at a given level of government and its sub-levels, also capture policies that the national government may specifically target at a subnational jurisdiction. This is the case, for example, if a national government orders events to close in a particular city experiencing an outbreak. These kinds of policies are not inferred from NAT_GOV but coded directly at the sub-national level.

For this US subnational repo, examples of policies included in STATE_WIDE involve state governments' policies, as well as county and city policies (the latter two would be coded as "targeted" STATE_WIDE policies per the [OxCGRT codebook](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md). This is a distinct data product from that found in the primary [OxCGRT/covid-policy-tracker](https://github.com/OxCGRT/covid-policy-tracker) data repo, where subnational data includes inherited policies from higher levels that affect that jurisdiction.

### Further interpretation

Flags representing distinctions between targeted/general measures for subnational data products are consistent with those in the existing OxCGRT [codebook](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md). 

### Our documentation and working papers have more information

The US subnational [working paper](https://www.bsg.ox.ac.uk/research/publications/variation-us-states-responses-covid-19) describes the subnational US methodology, data collection protocols, and indicator descriptions.

### Getting data from this GitHub repository

The [/data](data/) folder in this repo contains recent exports from the OxCGRT database. You are welcome to build applications that draw directly from this repository. The data is a full export from the database presented in "state-day" format, with a column of notes from our data collectors for each indicator. This is updated manually on a regular basis, and so the file name may change. Please note that some of the comments contain commas and other characters interpreted as a delimiter, and so may cause problems when parsing this CSV file.


### Acknowledgments

The OxCGRT USA subnational coders are: Alonso Moran de Romana, Andrew Brown, Anna Petherick, Anna Welsh, Anthony Sudarmawan, Ariq Hatibie, Arthur Lau, Beatriz Kira, Cassy Inman, Christian Lumley, Dang Dao Nguyen, Diane Brandt, Edward O'Brien, Emily Cameron-Blake, Emma Leonard, Helen Tatlow, India Clancy, Jeanna Kim, Joy Carveth, Kaitlyn Green, Katherine McCreery, Kelly Daniels, Kristie Jameson, Laura Chamberlain, Laura de Lisle, Laura Hallas, Leanne Giordono, Mariam Raheem, Marie Mavrikios, Michelle Sharma, Monika Pyarali, Nadine Dogbe, Nate Dolton-Thornton, Nikhil Tekwani, Paraskevas Christodoulopoulos, Quynh Lam Vo, Rachel Dixon, Rahima Hanifa, Raymond Pottebaum, Rene' Landers, Saptarshi Majumdar, Sara Sethia, Sena Pradipta, Seun Adebayo, Stephanie Guyett, Thomas Hale, Tim Nusser, Toby Phillips, Veronique Gauthier, Zara Raheem, Zoha Imran
