# chinese-student-dummy-database
### TO DO
1. Reports by Class
    * *AUTOMATE FOR ALL CLASSES*
        * [x] Basic DFs
        * Plots 
            * Test Scores
            * Homework Scores
            * Attendance
            * Participation
                * Participation type Distribution
                * Cold/Volunteer Ratio
                * Participation Instances count
                * Mean Participations for each student by class
                * Attempts per participation
                * Hints per participation
                * Attempt/Hint Ratio
            * Points
                * Total Points
    * [x] *Prepare DataFrames*
        * [x] All Classes
            * [x] Filter by year & month
        * [x] User-input Class
            * [x] Filter by year & month
    * *Plots*
        * [x] Test Scores
            * [x] Show test before last grade
            * [x] Show this test's average from the class
        * [x] Homework Scores
            * [x] All HW grades for the month
            * [x] Use subplots to get one plot per ID?
                * [x] Average lines are all on the last plot
            * [x] show HW grade average for each ID
        * [x] Attendance
            * [x] Define a list of the each absent instance and what dates
        * [x] Participation
            * [x] Participation type Distribution
                * [x] Current Month
            * [x] Cold/Volunteer Ratio
                * [x] Current Month
            * [x] Participation Instances count
                * [x] Current month
                * [x] Class Average
            * [x] Mean Participations for each student by class
                * [x] This month's average per student
                * [x] Class average for this month
            * [x] Attempts per participation
                * [x] This month's average per student
                * [x] Class average for this month
            * [x] Hints per participation
                * [x] This month's average
                * [x] Class average for this month
            * [x] Attempt/Hint Ratio
                * [x] This months
        * Points
            * [x] DataFrame
                * [x] Participation points
                * [x] HW points
                * [x] Test points
                * [x] Attendance points
                * [x] Total points
            * [x] Plots
                * [x] Total Points
    * *Automate Insights*
        * Test Scores
        * Homework Scores
        * Attendance
        * Participation
            * If Cold Call > Volunteer -> Student should try to volunteer more
            * If count is less than average -> Student should try to participate more || teacher should try to call on them more
        * Points 
2. Reports by Student
3. Convert Databases into SQL