# USA-subnational Covid-19 Policy Responses
Systematic dataset of US sub-national Covid-19 policy data

This is a project from the [Blavatnik School of Government](www.bsg.ox.ac.uk), drawing on the [Blavatnik School of Government OxCGRT](https://www.bsg.ox.ac.uk/covidtracker).

More information is available on the project's website: [https://www.bsg.ox.ac.uk/research/research-projects/brazils-covid-19-policy-response](https://www.bsg.ox.ac.uk/research/research-projects/brazils-covid-19-policy-response).

---

__Cite as:__ Thomas Hale, Sam Webster, Anna Petherick, Toby Phillips, and Beatriz Kira. (2020). _Oxford COVID-19 Government Response Tracker_. Blavatnik School of Government.

---

### Dataset of USA sub-national Covid-19 government response policies
Drawing on the Oxford COVID-19 Government Response Tracker (OxCGRT) [coding system](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md), we provide a systematic and objective account of the strength of Covid-19 response policies that have been instigated by the USA’s national government, state governments, and governments of Washington DC and the US Virgin Islands. Currently we provide coding up to 31 July 2020 for 13 indicators: C1 through C8, E1, E2, and H1 through H3. These indicators allow creation of four different [indices](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/index_methodology.md): the stringency index, containment and health index, government response index, and economic support index. These data are presented separately from the primary OxCGRT repo, but may be later incorporated into the primary OxCGRT codebook.

### Differences from primary OxCGRT data 
This repo contains data for two jurisdictions, described using the suffixes of "GOV" and "ALL." Policies described with the suffix "GOV" refers to policies issued by a specific level of government, and can be used to compare government responses across different levels of government. Policies with the suffix "ALL" describe all government responses relevant to a given jurisdiction. The USA subnational repo contains two descriptive labels:
- NAT_GOV: Policies issued by the USA federal government only.
- STATE_ALL: Policies issued by state governments and by sub-state governments.

For this repo's STATE_ALL distinction, the "ALL" suffix observations do not incorporate policies from higher levels of government that may supercede local policies. For example, if a country has an international travel restriction that applies country-wide, this would appear as a NAT_GOV policy and not within STATE_ALL. For this US subnational repo, examples of policies included in STATE_ALL involve state governments' policies, as well as county and city policies (the latter two would be coded as "targeted" STATE_ALL policies per the masterOxCGRT [codebook](documentation/codebook.md). This is a distinct data product from that found in the [primary](https://github.com/OxCGRT/covid-policy-tracker) OxCGRT data repo, where subnational data includes inherited policies from higher levels that affect that jurisdiction.

### Further interpretation
Indicator meanings and interpretation of targeted/general distinctions for subnational data products are consistent with those in the existing OxCGRT [codebook](documentation/codebook.md). 

### Our documentation and working papers have more information
The US subnational [working paper](https://www.bsg.ox.ac.uk/research/publications/variation-USstate-responses-covid-19) describes the subnational US methodology, data collection protocols, and indicator descriptions.

### Getting data from this GitHub repository
The [/data](data/) folder in this repo contains recent exports from the OxCGRT database. You are welcome to build applications that draw directly from this repository.

The CSV file [/data/OxCGRT_US_states_temp.csv](data/OxCGRT_US_states_temp.csv) is a full export from the database presented in "state-day" format, with a column of notes from our data collectors for each indicator. This is updated manually on a weekly basis. Please note that some of the comments contain commas and other characters interpreted as a delimiter, and so may cause problems when parsing this CSV file.


### Acknowledgments
The OxCGRT USA subnational coders are: Alonso Moran de Romana, Andrew Brown, Anna Petherick, Anna Welsh, Anthony Sudarmawan, Ariq Hatibie, Arthur Lau, Beatriz Kira, Cassy Inman, Christian Lumley, Dang Dao Nguyen, Diane Brandt, Edward O'Brien, Emily Cameron-Blake, Emma Leonard, Helen Tatlow, India Clancy, Jeanna Kim, Joy Carveth, Kaitlyn Green, Katherine McCreery, Kelly Daniels, Kristie Jameson, Laura Chamberlain, Laura de Lisle, Laura Hallas, Leanne Giordono, Mariam Raheem, Marie Mavrikios, Michelle Sharma, Monika Pyarali, Nadine Dogbe, Nate Dolton-Thornton, Nikhil Tekwani, Paraskevas Christodoulopoulos, Quyn Lam Vo (Lam), Rahima Hanifa, Raymond Pottebaum, Rene' Landers, Saptarshi Majumdar, Sara Sethia, Sena Pradipta, Seun Adebayo, Stephanie Guyett, Thomas Hale, Tim Nusser, Toby Phillips, Veronique Gauthier, Zara Raheem, Zoha Imran
