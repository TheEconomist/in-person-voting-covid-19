# in-person-voting-covid-19

---- Description ----
* Code and data for graphic detail on in-person voting and covid spread
* Link: https://www.economist.com/graphic-detail/2021/07/10/in-person-voting-really-did-accelerate-covid-19s-spread-in-america

---- Files ----
 * state_subset.csv: vote, covid, and demographic data by county for states for which there is complete data on in-person voting
 * fips_df.csv: fips code by state and county for merging data
 * temperatures.csv: average temperatures by county
 * county_covid.csv: covid cases by county (used for placebo test)
 * Markdown.Rmd: analysis (model & robustness checks)

---- Sources ----

States' Election Data: 
 * alabama: https://www.sos.alabama.gov/alabama-votes/voter/election-data
 * arizona: https://azsos.gov/2020-election-information/county-canvass-returns
 * arkansas: https://results.enr.clarityelections.com/AR/106124/web.274956/#/summary
 * california: https://elections.cdn.sos.ca.gov/sov/2020-general/sov/03-voter-participation-stats-by-county.pdf
 * florida: https://dos.myflorida.com/elections/data-statistics/elections-data/
 * georgia: https://results.enr.clarityelections.com/GA/105369/web.264614/#/summary
 * indiana: https://enr.indianavoters.in.gov/site/index.html
 * iowa: https://sos.iowa.gov/elections/results/precinctvotetotals2020general.html
 * louisiana: https://voterportal.sos.la.gov/graphical
 * maryland: https://elections.maryland.gov/elections/2020/election_data/index.html
 * new hampshire: https://sos.nh.gov/elections/elections/election-results/2020/general-election/
 * new mexico: https://electionresults.sos.state.nm.us/resultsSW.aspx?type=FED&map=CTY
 * north carolina: https://dl.ncsbe.gov/?prefix=ENRS/2020_11_03/results_precinct_sort/
 * ohio: https://www.ohiosos.gov/elections/election-results-and-data/2020/?__cf_chl_jschl_tk__=781ee9b9cd16c4aa51a652e51d7770f31436e32f-1615850975-0-AVeTCVgfWV7FPoZKgT0aSykOLUoEetH8tzVKoCstEJq7sLc0A_K_jnQkTZGci5QoaX2Er4i_MIoWm5RPgaU33GnB4Tu8Q01T64bjA1s9jULUnLgu-Thm0vaHr360pMoiay4Nnh6Zzj1jIbTKqSmNYw2kTet_42vrPUQPai7GDOSdxGECHNDpwIidIXpWeX-xtMNJWSVu2TPM6cmYCC6-raJ0I3UsuniW0Jo0RtkLHjsR3V14ObhkPeOY7UVnj6oiqmT6WiU278D0ToZnUxFPLGlNiAAXw_HnH2Ry4qXlrmL3Y1_8dZfaUc9gs-5r7QTu2igvNyTL1JuHOKqgWRStoEG5VcoKKRvPcA0HVFVIuMLtd2F-w5h5pBF7ah6DCIyeFRGMfEYtIUM7kEVp0bzpPBWPurd3e6_4bP3EckH-VVrsnjhkja663abnBkSpNICvuA
 * oklahoma: https://results.okelections.us/OKER/?elecDate=20201103
 * pennsylavnia: https://www.electionreturns.pa.gov/ReportCenter/Reports
 * rhode island: https://www.ri.gov/election/results/2020/general_election/
 * south carolina: https://results.enr.clarityelections.com/SC/106502/Web02-state.264691/#/access-to-races?undefined
 * vermont: https://sos.vermont.gov/elections/election-info-resources/elections-results-data/
 * virginia: https://results.elections.virginia.gov/vaelections/2020%20November%20General/Site/Statistics/Turnout.html

Covid Data:
 * from https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv

Demographic Data:
 * county-level demographics from https://data.hrsa.gov/data/download?data=AHRF#AHRF
 * Trump vote share from https://github.com/tonmcg/US_County_Level_Election_Results_08-20/blob/master/2016_US_County_Level_Presidential_Results.csv 



