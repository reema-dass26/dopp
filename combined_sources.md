# Sources for graduation data

## Default

If no source is mentioned, data is taken from
[the main csv file.](primary-completion-rate-combined.csv)

If a source provides data for a period overlapping two years (e.g. 2019/20), the latter year is chosen as date (e.g. 2020).

### Completion rate definition

Primary completion rate, or gross intake ratio to the last grade of primary education, is the number of new entrants (enrollments minus repeaters) in the last grade of primary education, regardless of age, divided by the population at the entrance age for the last grade of primary education. Data limitations preclude adjusting for students who drop out during the final year of primary education.

### Limitations and Exceptions

Data limitations preclude adjusting for students who drop out during the final year of primary education. Thus this rate is a proxy that should be taken as an upper estimate of the actual primary completion rate. There are many reasons why the primary completion rate can exceed 100 percent. The numerator may include late entrants and overage children who have repeated one or more grades of primary education as well as children who entered school early, while the denominator is the number of children at the entrance age for the last grade of primary education.

## CHN
[Overview of educational achievements in China in 2019](http://en.moe.gov.cn/documents/reports/202102/t20210209_513095.html)
[Overview of educational achievements in China in 2018](http://en.moe.gov.cn/documents/reports/201910/t20191022_404775.html)
[Major educational achievements in China in 2020](http://en.moe.gov.cn/features/2021TwoSessions/Reports/202103/t20210323_522026.html)

### Completion Rate Definition

Ratio of enrollment to graduation of compulsory education. 
Compulsory education starts at 6 (or 7 for exceptions) and lasts 9 years. [Compulsory Education Law of the People’s Republic of China](http://en.moe.gov.cn/documents/laws_policies/201506/t20150626_191391.html) Article 11, Article 2.

## IDN

No additional data.

## BRA

No additional data.

## NGA
[Statista (2020)](https://www.statista.com/statistics/1128794/school-completion-rate-in-nigeria-by-educational-level/) - 

### Completion Rate Definition

Number of children or young people aged 3-5 years above the intended age for the last grade of primary education who have completed the last grade of primary school.

## BGD
Bangladesh Education Fact Sheet 2019 (`./datasets/doc/Bangladesh-Education-Fact-Sheets_V7.pdf`)

### Completion Rate Definition

**MICS-EAGLE**:

The completion rate reflects the percentage of a cohort of
children or young people three to five years older than the
intended age for the last grade of each level of education
(primary, lower secondary, or upper secondary) who have
completed that level of education. For example, if the
official age of entry into primary education is 6 years, and
primary school has 5 grades, then the intended age for the
last grade of primary education is 10 years. In this case,
the reference age group for calculation of the primary
completion rate would be 13-15 years (10 + 3 = 13 and
10 + 5 = 15). This indicator is used to calculate SDG 4.1.2
– Completion rate (primary education, lower secondary
education, upper secondary education).

## JPN

## VNM
[Viet Nam SDGCW Survey 2020-2021 (for 2021)](https://www.unicef.org/vietnam/media/8686/file/Education.pdf)

### Completion Rate Definition

**MICS**:
Percentage of children age 3-5 years
above the intended age for the last grade
of primary school who have completed
primary education

## COD

No additional data.

## IRN
[World Bank (2019-2020)](https://data.worldbank.org/indicator/SE.PRM.CMPT.ZS?end=2020&locations=IR&start=2017&view=chart)

### Completion Rate Definition

Same as original source

## FRA

No additional data.

## MMR
[Myanmar 2019-2020 Education Budget Brief (Data from 2017/18 and 2018/2019, used for 2019)](https://www.unicef.org/myanmar/media/6461/file/2019-20%20Myanmar%20Education%20Budget%20Brief.pdf) 

**Conflicts with initial data!**

### Completion Rate Definition

Unknown; data provided by MoE, could not find original source.

## KEN

[Ministry of Education (2019)](https://africacheck.org/sites/default/files/Kenya-Basic-Education-Statistical-Booklet-2019.pdf)

**No conflict, but sudden drop.**

### Completion Rate Definition

Number of students finishing last stage of primary education divided by number of students who enrolled in the first stage *n* years earlier, where *n* is the duration of all primary education stages.

[...] Data in Table 11 shows that 82% of pupils who joined standard one in 2012 were enroled in
standard eight in 2019. The proportion of those completing standard eight dropped by two
percentage points between 2018 and 2019. Primary to Secondary Transition Rate increased by 12
percentage points between 2018 and 2019. Furthermore, nearly all learners who sat for their end
of primary cycle exams in 2018 joined Form one in 2019. This increase in transition rate is
largely attributed to the implementation of the 100 percent transition policy of the government.

# Summary of differences

The primary dataset treats "completion" as enrollment in the last grade of primary education. This, as stated in the original definition, does not consider students dropping out in the last grade. The rate of completion is calculated by dividing the number of enrollments by the number of people at the foreseen age of enrollment for the last grade. 

Other countries may define completion rate differently in their official reports. Examples include:
 - Graduation of last grade as a condition for "completion" (MICS, MICS-EAGLE, China, Kenya).
 - Division by first-year enrollments as opposed to elligible population (China, Kenya).
 - Percentage of children above a certain age who graduated from the last grade (MICS, MICS-EAGLE).
 - A different definition of "primary school", i.e. possible incompatibilities to ISCED-1 (Difficult to determine).