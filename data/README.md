# Data for replication

### Here is the data needed for replicating the experiments on WPI datasets across the three academic years of 2017-2018, 2018-2019, and 2019-2020. The dataset contained in each folder represents an academic year and includes the following material in four .csv files:

- *student_preference.csv* contains an $|\mathcal{S}|\times|\mathcal{P}|$ matrix of student preferences where an entry $(s,p)$ in index $s$ and column $p$ indicates a preference value of student $s$ at project center $p$. These values are in $\\{1, 0.5, 0\\}$.
- *project_preference.csv* contains an $|\mathcal{S}|\times|\mathcal{P}|$ matrix of project director preferences where an entry $(s,p)$ in index $s$ and column $p$ indicates a preference value of project director $p$ on student $s$. These values range between 0 and 1.
- *project_capacity.csv* contains the capacity of each project center where each row is a tuple of ProjectID and the corresponding Capacity.
- *student_info.csv* contains the gender and major of students where each row is a tuple of StudentID, Gender, and Major.

Note: The present matching process requires students to rate each project center in one of three tiers as *Very Interested*, *Interested*, or *Not Interested*, which are assigned student utility weights of 1, 0.5, and 0, respectively. In an effort to increase access, students are required to choose at least three project centers in the *Very Interested* tier and at least six options in the *Very Interested* and *Interested* tiers, combined. However, this requirement was applied after the academic year 2017-2018; moreover, during the process of selecting the final match outcome, administrators removed some project centers that lacked sufficient interest from students. Therefore, the final WPI datasets in the academic years 2018-2019 and 2019-2020 contain some select students where the number of rated project centers does not strictly adhere to the requirement.
