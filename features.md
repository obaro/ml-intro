| Variable Name | Description |Role | Type |
|---------------|-------------|-----|-----|
|school | student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira) | Feature | Categorical |
|sex | student's sex (binary: 'F' - female or 'M' - male) | Feature | Binary |
|age | student's age (numeric: from 15 to 22) | Feature | Integer |
|address | student's home address type (binary: 'U' - urban or 'R' - rural) | Feature | Categorical |
|famsize | family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3) | Feature | Categorical |
|Pstatus | parent's cohabitation status (binary: 'T' - living together or 'A' - apart) | Feature | Categorical |
|Medu | mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3 - secondary education or 4 - higher education) | Feature | Integer |
|Fedu | father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 â€“ 5th to 9th grade, 3 â€“ secondary education or 4 â€“ higher education) | Feature | Integer |
|Mjob | mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other') | Feature | Categorical |
|Fjob | father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other') | Feature | Categorical |
|reason | reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other') | Feature | Categorical |
|guardian | student's guardian (nominal: 'mother', 'father' or 'other') | Feature | Categorical |
|traveltime | home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour) | Feature | Integer |
|studytime | weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours) | Feature | Integer |
|failures | number of past class failures (numeric: n if 1<=n<3, else 4) | Feature | Integer |
|schoolsup | extra educational support (binary: yes or no) | Feature | Binary |
|famsup | family educational support (binary: yes or no) | Feature | Binary |
|paid | extra paid classes within the course subject (Math or Portuguese) (binary: yes or no) | Feature | Binary |
|activities | extra-curricular activities (binary: yes or no) | Feature | Binary |
|nursery | attended nursery school (binary: yes or no) | Feature | Binary |
|higher | wants to take higher education (binary: yes or no) | Feature | Binary |
|internet | Internet access at home (binary: yes or no) | Feature | Binary |
|romantic | with a romantic relationship (binary: yes or no) | Feature | Binary |
|famrel | quality of family relationships (numeric: from 1 - very bad to 5 - excellent) | Feature | Integer |
|freetime | free time after school (numeric: from 1 - very low to 5 - very high) | Feature | Integer |
|goout | going out with friends (numeric: from 1 - very low to 5 - very high) | Feature | Integer |
|Dalc | workday alcohol consumption (numeric: from 1 - very low to 5 - very high) | Feature | Integer |
|Walc | weekend alcohol consumption (numeric: from 1 - very low to 5 - very high) | Feature | Integer |
|health | current health status (numeric: from 1 - very bad to 5 - very good) | Feature | Integer |
|absences | number of school absences (numeric: from 0 to 93) | Feature | Integer |
|G1 | first period grade (numeric: from 0 to 20) | Target | Categorical |
|G2 | second period grade (numeric: from 0 to 20) | Target | Categorical |
|G3 | final grade (numeric: from 0 to 20, output target) | Target | Integer |