---
title: COVID-19 Reported Patient Impact and Hospital Capacity by Facility
created: '2021-03-29T23:32:58.657173'
modified: '2021-05-15T11:12:10.340572'
state: active
type: dataset
tags:
  - Covid 19
  - Hhs Covid 19
groups: []
csv_url: 'https://healthdata.gov/api/views/anag-cw7u/rows.csv?accessType=DOWNLOAD'
json_url: 'https://healthdata.gov/api/views/anag-cw7u/rows.json?accessType=DOWNLOAD'
layout: post

---
The following dataset provides facility-level data for hospital utilization aggregated on a weekly basis (Friday to Thursday). These are derived from reports with facility-level granularity across two main sources: (1) HHS TeleTracking, and (2) reporting provided directly to HHS Protect by state/territorial health departments on behalf of their healthcare facilities.

The hospital population includes all hospitals registered with Centers for Medicare & Medicaid Services (CMS) as of June 1, 2020. It includes non-CMS hospitals that have reported since July 15, 2020. It does not include psychiatric, rehabilitation, Indian Health Service (IHS) facilities, U.S. Department of Veterans Affairs (VA) facilities, Defense Health Agency (DHA) facilities, and religious non-medical facilities.

For a given entry, the term “collection_week” signifies the start of the period that is aggregated. For example, a “collection_week” of 2020-11-20 means the average/sum/coverage of the elements captured from that given facility starting and including Friday, November 20, 2020, and ending and including reports for Thursday, November 26, 2020.

Reported elements include an append of either “_coverage”, “_sum”, or “_avg”.
<ul>
<li>A “_coverage” append denotes how many times the facility reported that element during that collection week.</li>
<li>A “_sum” append denotes the sum of the reports provided for that facility for that element during that collection week.</li>
<li>A “_avg” append is the average of the reports provided for that facility for that element during that collection week.</li></ul>

The file will be updated weekly. No statistical analysis is applied to impute non-response. For averages, calculations are based on the number of values collected for a given hospital in that collection week. Suppression is applied to the file for sums and averages less than four (4). In these cases, the field will be replaced with “-999,999”.

This data is preliminary and subject to change as more data become available. Data is available starting on July 31, 2020.

Sometimes, reports for a given facility will be provided to both HHS TeleTracking and HHS Protect. When this occurs, to ensure that there are not duplicate reports, deduplication is applied according to prioritization rules within HHS Protect.

For influenza fields listed in the file, the current HHS guidance marks these fields as optional. As a result, coverage of these elements are varied.</li></ul>

</ul>On May 3, 2021, the following fields have been added to this data set.
<li>hhs_ids
<li>previous_day_admission_adult_covid_confirmed_7_day_coverage
<li>previous_day_admission_pediatric_covid_confirmed_7_day_coverage
<li>previous_day_admission_adult_covid_suspected_7_day_coverage
<li>previous_day_admission_pediatric_covid_suspected_7_day_coverage
<li>previous_week_personnel_covid_vaccinated_doses_administered_7_day_sum
<li>total_personnel_covid_vaccinated_doses_none_7_day_sum
<li>total_personnel_covid_vaccinated_doses_one_7_day_sum
<li>total_personnel_covid_vaccinated_doses_all_7_day_sum
<li>previous_week_patients_covid_vaccinated_doses_one_7_day_sum
<li>previous_week_patients_covid_vaccinated_doses_all_7_day_sum</li></ul>

</ul>On May 8, 2021, this data set has been converted to a corrected data set.  The corrections applied to this data set are to smooth out data anomalies caused by keyed in data errors.  To help determine which records have had corrections made to it.   An additional Boolean field called is_corrected has been added.  To see the numbers as reported by the facilities, go to:
https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/uqq2-txqb </li></ul>

</ul>On May 13, 2021 Changed vaccination fields from sum to max or min fields.  This reflects the maximum or minimum number reported for that metric in a given week.</li></ul>
