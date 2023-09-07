

**Title:** Comparing Closing Ranks of Two Engineering Institutions

**Description:**
This Python script creates bar plots to compare the closing ranks of two engineering institutions, "Anurag group of Institutions (ANRK)" and "Sreyas Institute of Engineering and Technology (SIET)," using the Pandas, Seaborn, and Matplotlib libraries. The script reads data from two CSV files, 'REALANUR.csv' and 'SREYAS1.csv,' and visualizes the closing ranks for various branches in each institution.

**Requirements:**
- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- 'REALANUR.csv' (data for ANRK) and 'SREYAS1.csv' (data for SIET) should be present in the same directory as this script.

**Usage:**
1. Ensure you have the required Python libraries installed.
2. Place the 'REALANUR.csv' and 'SREYAS1.csv' files in the same directory as this script.
3. Run the script.

**Code Explanation:**
- The script imports the necessary libraries: Pandas, Seaborn, and Matplotlib.
- It reads data from 'REALANUR.csv' into the 'df' DataFrame and 'SREYAS1.csv' into the 'df1' DataFrame.
- Two separate bar plots are created for each institution's closing ranks using Seaborn's `sns.barplot()`.
- The script sets appropriate labels and titles for each plot.
- Lastly, it combines both bar plots into a single plot, differentiating the institutions using green (SIET) and blue (ANRK) bars.

**Visualization:**
- The first two plots show the closing ranks of ANRK and SIET separately.
- The third plot combines both institutions' closing ranks for easy visual comparison, with green bars representing SIET and blue bars representing ANRK.

**Output:**
- Running the script will display three bar plots:
  1. Closing ranks for ANRK.
  2. Closing ranks for SIET.
  3. A combined comparison plot of both institutions' closing ranks.

---

Please ensure you have the necessary libraries and data files in place before running the script.
