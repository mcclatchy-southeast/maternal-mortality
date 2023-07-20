# Pregnancy-related deaths in North Carolina

[Initially prompted](https://github.com/MuckRock/maternal-mortality) by the release of data from the nonprofit journalism organization MuckRock, reporters at The News & Observer in early March set out to examine why more women in the U.S. and North Carolina are dying of pregnancy-related complications.

## Read the series

* [Pregnancy can be risky in the U.S. In North Carolina, the threat is even higher.](https://www.newsobserver.com/news/state/north-carolina/article277397263.html)<br />July 19, 2023 // Teddy Rosenbluth & Tyler Dukes

* [Maternal deaths just ‘one part of the story’ in NC. Pregnancy complications are rising](https://www.newsobserver.com/news/state/north-carolina/article277056348.html)<br />July 19, 2023 // Tyler Dukes & Teddy Rosenbluth

* [Weary of lopsided birth risks, Charlotte women expand care for Black women themselves](https://www.charlotteobserver.com/news/state/north-carolina/article276965933.html)<br />July 19, 2023 // Lisa Vernon Sparks

* [Pregnancy-related deaths open voids in families expecting to celebrate new life](https://www.newsobserver.com/news/state/north-carolina/article277398108.html)<br />July 19, 2023 // Tyler Dukes & Ethan Hyman

* [Five takeaways from investigating pregnancy-related deaths in NC](https://www.newsobserver.com/news/state/north-carolina/article277276748.html)<br />July 20, 2023 // Tyler Dukes, Teddy Rosenbluth & Lisa Vernon Sparks

## How we did this story

National and international health agencies have slightly different ways to define pregnancy-related deaths.

The N&O used the definition of the [Centers for Disease Control and Prevention](https://www.cdc.gov/reproductivehealth/maternal-mortality/pregnancy-mortality-surveillance-system.htm#:~:text=defines%20a%20pregnancy%2Drelated%20death%20as%20a%20death%20while%20pregnant%20or%20within%201%20year%20of%20the%20end%20of%20pregnancy%20from%20any%20cause%20related%20to%20or%20aggravated%20by%20the%20pregnancy.) and [research by Marie Thoma](https://www.documentcloud.org/documents/23720948-changes_in_pregnancy_related_mortality_associated721), of the University of Maryland School of Public Health, which count as pregnancy-related any deaths "from any cause related to or aggravated by the pregnancy" within a year of being pregnant. This includes all death certificates with medical codes for obstetrical tetanus (ICD-10 codes A34) and diseases/injuries related to pregnancy, childbirth and the postpartum period (O00-O96 and O98-O99).

N&O reporters obtained data on these deaths – both for individual states and the U.S. overall – through the [CDC's online WONDER tool](https://wonder.cdc.gov/controller/saved/D158/D330F878) for the years 2018 to 2021. Data from years prior to 2018, experts said, were less reliable because of substantial changes in the way pregnancy-related deaths were tracked state by state.

Because the CDC suppresses death totals for some states where the figures are low enough to risk patient privacy, not all states are represented in the data. The CDC warns against comparisons and rankings state-by-state.

Rates are calculated per 100,000 live births, according to annual final reports from the [National Vital Statistics System](https://www.cdc.gov/nchs/nvss/births.htm).

The N&O used the same methodology to examine racial disparities in pregnancy-related deaths using both CDC data and the State Center for Health Statistics death certificate database through a 2020 data use agreement with the N.C. Department of Health and Human Services. In some cases, figures from this data, which only tracks the death of North Carolina residents who die in the state, differ slightly from data from the CDC, which counts deaths by residency regardless of where they died.

State Health Statistics death certificate data from 2022 is still preliminary.

To gauge the direct impact of the coronavirus pandemic, reporters also analyzed state death certificate data listing the medical code for COVID-19 (ICD-10 code U071) as a contributing cause of death along with a pregnancy-related underlying cause of death.

The N&O also obtained data from N.C. DHHS based on hospital discharges related to severe maternal morbidity. These so-called "near misses" occur when a pregnant woman almost dies from a list of serious maternal injuries or illnesses [defined by the Alliance for Innovation on Maternal Health](https://saferbirth.org/wp-content/uploads/AIM-SMM-Code-List_04042023.xlsx).

Severe maternal morbidity data from 2022 is still provisional.

## Get the data

The following files can be downloaded from the `data` directory in this repository. Full tables are below.

* [Pregnancy-related death counts and rates by state](/data/cdc_pregnancy_related_deaths2018_2021.csv)<br />
CDC data on the number of deaths due to ICD-10 codes associated with pregnancy-related injuries and illnesses up to a year after pregnancy for all states with data from 2018-2021.
* [Pregnancy-related death counts and rates in NC by race](/data/cdc_pregnancy_related_deaths2018_2021_nc_race.csv)<br />
CDC data on the number of deaths due to ICD-10 codes associated with pregnancy-related injuries and illnesses up to a year after pregnancy from 2018-2021 for non-Hispanic white and non-Hispanic Black residents of North Carolina. Live birth data comes from the National Vital Statistics System, and pregnancy-related death rates are calculated per 100,000 live births.
* [Pregnancy-related deaths and COVID](/data/nc_vital_pregnancy_related_deaths_covid2018_2021.csv)<br />
State death certificate data on the number of pregnancy-related deaths listing the ICD-10 code for COVID (U071) as a contributing cause of death along with a pregnancy-related underlying cause of death. *NOTE: 2022 data below from DHHS is preliminary as of July 2023 and is not final.*
* [Severe maternal morbidity counts for NC resident deliveries, 2018-2021](data/smm_data_26JUN2023.xlsx)<br />
N.C. DHHS data on severe maternal morbidity, based on hospital discharge data from 2018 to 2022, as of June 2023. *Note: The State Center for Health Statistics discharge data files are considered provisional and subject to change until they finalize their discharge data, which typically occurs within 2-3 years after the end of the calendar year.*

### Selected tables

#### Pregnancy-related death counts and rates by state

CDC data on the number of deaths due to ICD-10 codes associated with pregnancy-related injuries and illnesses up to a year after pregnancy for all states with data from 2018-2021. Live birth data comes from the National Vital Statistics System, and pregnancy-related death rates are calculated per 100,000 live births.

|Year |State          | Deaths|    Births|  Rate|
|:----|:--------------|------:|---------:|-----:|
|2018 |TOTAL          |    935| 3,791,712|  24.7|
|2019 |TOTAL          |  1,076| 3,747,540|  28.7|
|2020 |TOTAL          |  1,268| 3,613,647|  35.1|
|2021 |TOTAL          |  1,666| 3,664,292|  45.5|
|2018 |North Carolina |     24|   118,954|  20.2|
|2019 |North Carolina |     45|   118,725|  37.9|
|2020 |North Carolina |     66|   116,730|  56.5|
|2021 |North Carolina |     82|   120,466|  68.1|
|2018 |Alabama        |     31|    57,761|  53.7|
|2019 |Alabama        |     33|    58,615|  56.3|
|2020 |Alabama        |     34|    57,647|  59.0|
|2021 |Alabama        |     50|    58,054|  86.1|
|2018 |Arizona        |     22|    80,723|  27.3|
|2019 |Arizona        |     31|    79,375|  39.1|
|2020 |Arizona        |     39|    76,947|  50.7|
|2021 |Arizona        |     38|    77,916|  48.8|
|2018 |Arkansas       |     22|    37,018|  59.4|
|2019 |Arkansas       |     14|    36,564|  38.3|
|2020 |Arkansas       |     22|    35,251|  62.4|
|2021 |Arkansas       |     24|    35,965|  66.7|
|2018 |California     |     79|   454,920|  17.4|
|2019 |California     |     68|   446,479|  15.2|
|2020 |California     |     81|   420,259|  19.3|
|2021 |California     |     92|   420,608|  21.9|
|2018 |Florida        |     54|   221,542|  24.4|
|2019 |Florida        |     69|   220,002|  31.4|
|2020 |Florida        |     58|   209,671|  27.7|
|2021 |Florida        |    107|   216,260|  49.5|
|2018 |Georgia        |     61|   126,172|  48.3|
|2019 |Georgia        |     62|   126,371|  49.1|
|2020 |Georgia        |     49|   122,473|  40.0|
|2021 |Georgia        |     95|   124,073|  76.6|
|2018 |Illinois       |     22|   144,815|  15.2|
|2019 |Illinois       |     20|   140,128|  14.3|
|2020 |Illinois       |     37|   133,298|  27.8|
|2021 |Illinois       |     47|   132,189|  35.6|
|2018 |Indiana        |     23|    81,646|  28.2|
|2019 |Indiana        |     33|    80,859|  40.8|
|2020 |Indiana        |     33|    78,616|  42.0|
|2021 |Indiana        |     38|    79,946|  47.5|
|2018 |Kentucky       |     29|    53,922|  53.8|
|2019 |Kentucky       |     21|    53,069|  39.6|
|2020 |Kentucky       |     28|    51,668|  54.2|
|2021 |Kentucky       |     23|    52,214|  44.0|
|2018 |Louisiana      |     21|    59,615|  35.2|
|2019 |Louisiana      |     26|    58,941|  44.1|
|2020 |Louisiana      |     31|    57,328|  54.1|
|2021 |Louisiana      |     44|    57,437|  76.6|
|2018 |Maryland       |     17|    71,080|  23.9|
|2019 |Maryland       |     22|    70,178|  31.3|
|2020 |Maryland       |     18|    68,554|  26.3|
|2021 |Maryland       |     26|    68,285|  38.1|
|2018 |Michigan       |     19|   110,032|  17.3|
|2019 |Michigan       |     34|   107,886|  31.5|
|2020 |Michigan       |     38|   104,074|  36.5|
|2021 |Michigan       |     33|   104,980|  31.4|
|2018 |Minnesota      |     10|    67,344|  14.8|
|2019 |Minnesota      |     11|    66,027|  16.7|
|2020 |Minnesota      |     12|    63,443|  18.9|
|2021 |Minnesota      |     17|    64,425|  26.4|
|2018 |Mississippi    |     15|    37,000|  40.5|
|2019 |Mississippi    |     21|    36,636|  57.3|
|2020 |Mississippi    |     15|    35,473|  42.3|
|2021 |Mississippi    |     38|    35,156| 108.1|
|2018 |Missouri       |     24|    73,269|  32.8|
|2019 |Missouri       |     16|    72,127|  22.2|
|2020 |Missouri       |     39|    69,285|  56.3|
|2021 |Missouri       |     35|    69,453|  50.4|
|2018 |New Jersey     |     34|   101,223|  33.6|
|2019 |New Jersey     |     34|    99,585|  34.1|
|2020 |New Jersey     |     35|    97,954|  35.7|
|2021 |New Jersey     |     44|   101,497|  43.4|
|2018 |New York       |     65|   226,238|  28.7|
|2019 |New York       |     77|   221,539|  34.8|
|2020 |New York       |     70|   209,338|  33.4|
|2021 |New York       |     89|   210,742|  42.2|
|2018 |Ohio           |     27|   135,134|  20.0|
|2019 |Ohio           |     45|   134,461|  33.5|
|2020 |Ohio           |     43|   129,191|  33.3|
|2021 |Ohio           |     65|   129,791|  50.1|
|2018 |Oklahoma       |     17|    49,800|  34.1|
|2019 |Oklahoma       |     14|    49,143|  28.5|
|2020 |Oklahoma       |     12|    47,623|  25.2|
|2021 |Oklahoma       |     25|    48,410|  51.6|
|2018 |Pennsylvania   |     27|   135,673|  19.9|
|2019 |Pennsylvania   |     39|   134,230|  29.1|
|2020 |Pennsylvania   |     25|   130,693|  19.1|
|2021 |Pennsylvania   |     46|   132,622|  34.7|
|2018 |South Carolina |     16|    56,669|  28.2|
|2019 |South Carolina |     24|    57,038|  42.1|
|2020 |South Carolina |     31|    55,704|  55.7|
|2021 |South Carolina |     37|    57,185|  64.7|
|2018 |Tennessee      |     26|    80,751|  32.2|
|2019 |Tennessee      |     29|    80,450|  36.0|
|2020 |Tennessee      |     52|    78,689|  66.1|
|2021 |Tennessee      |     61|    81,717|  74.6|
|2018 |Texas          |     92|   378,624|  24.3|
|2019 |Texas          |     85|   377,599|  22.5|
|2020 |Texas          |    155|   368,190|  42.1|
|2021 |Texas          |    205|   373,594|  54.9|
|2018 |Virginia       |     21|    99,843|  21.0|
|2019 |Virginia       |     32|    97,429|  32.8|
|2020 |Virginia       |     44|    94,749|  46.4|
|2021 |Virginia       |     60|    95,825|  62.6|
|2018 |Washington     |     18|    86,085|  20.9|
|2019 |Washington     |     30|    84,895|  35.3|
|2020 |Washington     |     17|    83,086|  20.5|
|2021 |Washington     |     25|    83,911|  29.8|


#### Pregnancy-related death counts and rates in NC by race
CDC data on the number of deaths due to ICD-10 codes associated with pregnancy-related injuries and illnesses up to a year after pregnancy from 2018-2021 for non-Hispanic white and non-Hispanic Black residents of North Carolina. Live birth data comes from the National Vital Statistics System, and pregnancy-related death rates are calculated per 100,000 live births.

|year | Deaths, total| Births, total| Rate, total| Deaths, white| Births, white| Rate, white| Deaths, Black| Births, Black| Rate, Black|
|:----|-------------:|-------------:|-----------:|-------------:|-------------:|-----------:|-------------:|-------------:|-----------:|
|2018 |            24|       118,954|        20.2|            12|        63,514|        18.9|            10|        27,670|        36.1|
|2019 |            45|       118,725|        37.9|            16|        62,205|        25.7|            21|        27,733|        75.7|
|2020 |            66|       116,730|        56.5|            18|        60,518|        29.7|            39|        27,228|       143.2|
|2021 |            82|       120,466|        68.1|            36|        63,239|        56.9|            30|        27,028|       111.0|


#### Pregnancy-related deaths and COVID
State death certificates data on the number of pregnancy-related deaths listing the ICD-10 code for COVID (U071) as a contributing cause of death along with a pregnancy-related underlying cause of death. *NOTE: 2022 data below from DHHS is preliminary as of July 2023 and is not final.*

|Year | COVID listed| COVID not listed| Deaths, total|
|:----|------------:|----------------:|-------------:|
|2018 |            0|               19|            19|
|2019 |            0|               43|            43|
|2020 |            3|               63|            66|
|2021 |           26|               53|            79|
|*2022* |            *5*|               *51*|            *56*|