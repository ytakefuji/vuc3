# vuc3
This is under review.

vuc3.py is a Python program to invesitigate effects of vaccines on COVID-19 mortality and infection between the second booster, the fist booster, fully vaccinated and unvaccinated.

CDC dataset is used for this study:
https://data.cdc.gov/api/views/ukww-au2k/rows.csv

vuc3 is a PyPI application which runs on Windows, MacOS, and Linux Operating Systems
as long as Python is installed on the system. Three determinants should be given to uvc3 such as age group (50-64, 65+ or all_ages), product (Pfizer, Moderna, Janssen, and all_types), and outcome (death or case).

# How to install vuc3
$ pip install vuc3

# How to run vuc3
$ vuc3 all_ages Pfizer death
