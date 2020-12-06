# HRstaffrecords
HR data: staff records
Murilo Henrique Sisnando Rodrigues
The scenario:
The fictional wholesale company, CR25 (for “Classic Rock 25”), currently has 999 employees.

employee characteristics
The CSV file “df_HR_main.csv” contains the following variables:

emp_id – a unique identification number for each employee

start_date – the date the employee started their employment with CR25

four variables based on the designated groups specified in Canada’s Employment Equity Act, where “TRUE” indicates the the employee is a member of that group

women

Aboriginal peoples

persons with disabilities

members of visible minorities (meaning “persons, other than Aboriginal peoples, who are non-Caucasian in race or non-white in colour”).

transaction history
Some of the employees in this company have been with the company since it started on 2010-01-01, and others started recently.

There are 5 occupations in the company, labelled A (for Apprentice) to E (for Executive), and each has more responsibility (and therefore pay) than the one below. Employees can start at any one of the occupations, and are eligible for a promotion after 90 days on the job (but some people take longer than that).

Each occupation has 3 steps (numbered 1 to 3); everyone starts at step 1, and moves to step 2 after 1 year in that occupation, and step 3 after 2 years.

The second CSV file “df_HR_transaction.csv” contains the promotion history for each employee. The variables are:

emp_id – a unique identification number for each employee

transaction_num – the hiring and promotion event categories

transaction_date – the date of the hiring and promotion event

occupation – the five occupation categories

occ_step – the annual increment steps

