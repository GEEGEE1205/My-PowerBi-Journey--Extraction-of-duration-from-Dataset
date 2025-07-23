###  Power BI Training Project – Duration Transformation & Date Intelligence

  **Project Overview**

-  This Power BI report demonstrates practical application of Power Query and Date Intelligence skills. The objective was to transform raw date data into meaningful temporal insights using Power BI’s Power Query Editor. This project focuses on enhancing datasets through column management,duration calculations, and date-based logic, paving the way for more insightful reporting.

---

 **Skills Demonstrated & How They Were Achieved**

 1. Column Management

    - Re-ordering Columns: In Power Query, I clicked and dragged columns into a preferred order to improve readability and logical structure.Organizing columns logically helps during analysis and eases navigation.
      
    - Removing Columns: I selected unnecessary columns, right-clicked, and chose “Remove” to eliminate them from the query. Reducing clutter enhances performance and focuses the dataset on relevant fields only.

    - Renaming Columns: By double-clicking on column headers or using the "Transform" tab → "Rename". Renaming improves clarity, standardization, and consistency throughout the dataset.

---

 2. Date Intelligence Features

     - Inserted Start of Year: From a date column, I used:

       - Add Column → Date → Year → Start of Year
          - Result: A column showing dd-mm-yyyy for each date.
          - Importance: Enables grouping and comparison across different years.

    - Inserted End of Year:
       - Via Add Column → Date → Year → End of Year
          - Result: A column displaying dd-mm-yyyy for each entry.
          - Importance: Helps calculate remaining time in the year or full-year summaries.

   - Inserted Day of Week
     - Add Column → Date → Day → Name of Day
        - Result: A new column showing the weekday name (e.g., Monday, Tuesday).
        - Importance: Enables weekday trend analysis.

  - Inserted Start of Day
    - Used Add Column → Date → Time → Start of Day
       - Result: Extracted the timestamp marking the beginning (12:00 AM) of each date.
       - Importance: Useful in time-based data filtering and modeling.

---

 3. Duration Calculations

     - Age Calculation
       - Used Add Column → Date → Age by comparing a date (e.g., birthdate) to the current or reference date.
          - Result: A duration value (in years, months, days).
          - Importance: Useful for analyzing customer age or time-based metrics.

    - Extract Total Years

      - After computing Age (duration), I used Transform → Duration → Total Years to extract only the year part.
         - Result: Numerical year value from duration.
         - Importance: Segmentation based on time intervals.

    - Round Down Values

      - Applied Transform → Rounding → Round Down to the Total Years column.
         - Result: Removed decimal places (e.g., 25.8 became 25).
         - Importance: Groups customers or records by completed full years only.

---

- **File Summary**

  - Filename: Inserting Duration.pbix
  - Tool: Power BI Desktop
  - Main Work Area: Power Query Editor
  - Focus: Transformation of date fields and duration calculations

---

- **Lessons Learnt**
 
  - Power Query Editor is a powerful tool for preparing data before visualization.
  - Date Intelligence enriches datasets for time-based analysis.
  - Duration calculations allow for deriving meaningful insights like age or service length.
  - Clean, well-structured datasets lead to better dashboards and business decisions.

