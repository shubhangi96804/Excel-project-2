# Excel-project-2
Audible Data cleaning project
Project Overview

This project involves cleaning and standardizing an Audible dataset using Power Query Editor in Excel. The dataset was transformed to ensure consistency and prepared for further analysis by applying various data cleaning and transformation techniques.
Dataset Link:

https://drive.google.com/file/d/1yjyozaSrwShoaROq-TDuSgC5HNLLmrTE/view?usp=sharing
Project Description:

Utilize Power Query Editor in Excel to clean and standardize an Audible dataset. Tasks include formatting columns, ensuring data consistency, and preparing the dataset for analysis.

    Standardize the name column to ensure consistent title casing.
    Separate combined first and last names in the author column if they are currently combined.
    Ensure all entries in the releasedate column follow a consistent date format (DD-MM-YYYY).
    Convert the time column from text format to a duration format that Excel recognizes.
    Ensure the price column is in a numeric format, and identify any non-numeric values.
    Convert text ratings in the stars column to numeric values.
    Split the narratedby column into multiple columns if multiple narrators are listed.
    Merge the releasedate and language columns into a single new column named releaseinfo with the format "DD-MM-YYYY, Language."
    Ensure all currency values in the price column are formatted consistently with two decimal places.

Data Cleaning Tasks and Applied Steps
1. Name Standardization

    Step Applied: Capitalized each word in the "Name" column to ensure uniform title casing.
    Explanation: This ensures that the product titles follow a consistent format, improving readability and data presentation.

2. Author Name Separation

    Step Applied: Split the "Author" column by delimiter or character transitions to separate first and last names.
    Explanation: When authors’ full names were combined, the column was split into separate fields for better data organization.

3. Release Date Standardization

    Step Applied: Converted the "ReleaseDate" column to a date format (DD-MM-YYYY).
    Explanation: Ensuring consistent date formats across the dataset allows for accurate analysis based on release dates.

4. Duration Conversion

    Step Applied:
        Extracted hours from the "Time" column.
        Converted hours to minutes using a multiplication formula.
    Explanation: The time values were transformed into a recognized Excel duration format, allowing for proper time calculations and analysis.

5. Price Column Cleanup

    Step Applied:
        Replaced non-numeric values (e.g., "Free") with "0."
        Changed the data type of the "Price" column to currency.
        Applied formatting to ensure all values have two decimal places.
    Explanation: This ensures all price entries are numeric and uniformly formatted, allowing for meaningful pricing analysis.

6. Star Rating Conversion

    Step Applied: Replaced text-based star ratings with numeric values.
    Explanation: This step facilitates easier analysis and calculations of product ratings.

7. Narrator Separation

    Step Applied:
        Split the "NarratedBy" column by delimiters (e.g., commas) to separate multiple narrators.
        Merged split narrator columns for clarity.
    Explanation: This helps identify individual narrators when multiple are listed for a single audiobook, improving the clarity of the dataset.

8. Merging Columns for Release Info

    Step Applied: Merged the "ReleaseDate" and "Language" columns into a new column "ReleaseInfo" with the format "DD-MM-YYYY, Language."
    Explanation: Combining these columns provides a comprehensive view of release information and simplifies the dataset.

9. Null Value Replacement

    Step Applied:
        Replaced null values in various columns with appropriate placeholders (e.g., "Not Applicable" or "0").
    Explanation: This ensures there are no gaps in the dataset, improving data integrity for further analysis.

Key Excel Features Used

    Power Query Editor: For column formatting, data splitting, and transformation tasks.
    Text to Columns: To separate combined names and narrators.
    Data Type Conversion: Converted text data types to appropriate formats like numeric and date.
    Merge Columns: Combined "ReleaseDate" and "Language" into a single column using custom formatting.
    Conditional Formatting: Applied for visual consistency checks.

Conclusion

The project effectively cleaned and standardized the Audible dataset, ensuring uniformity in column formats and preparing it for deeper analysis. Power Query Editor's transformation capabilities were pivotal in streamlining this process.
