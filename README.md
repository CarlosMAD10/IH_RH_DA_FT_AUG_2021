<!-----
NEW: Check the "Suppress top comment" option to remove this info from the output.

Conversion time: 0.764 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β30
* Tue Aug 17 2021 23:37:22 GMT-0700 (PDT)
* Source doc: Week 1
* Tables are currently converted to HTML tables.
----->


**Data Analysis Bootcamp - Berlin**

**Today`s Learning Objectives:**



* Dataframe filtering
* apply functions on Data Frames
* using map function
* using Lambda functions
* dealing with missing values
* Working with Categorical variables
* Concatenating
* working with DateTime using Pandas
* Grouping using Pandas
* Correlation Matrix

**Index of Contents**


<table>
  <tr>
   <td colspan="5" ><strong>Week 2</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Day 1</strong>
   </td>
   <td><strong>Day 2</strong>
   </td>
   <td><strong>Day 3</strong>
   </td>
   <td><strong>Day 4</strong>
   </td>
   <td><strong>Day 5</strong>
   </td>
  </tr>
  <tr>
   <td>Weekly Retro
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Pandas/Notebook_Code_Along_RH_Pandas_Data_Frame_General.ipynb">[Code Along] Intro to Pandas</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1lunSe5OvOJmdKxFE2CkpsYnbyxAYpJ6u/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Basic Statistical Concepts</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1RP1DE_Tm8rOFKehDX0Zf6PeC0ffm8dLz/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] EDA with plotting</a>
   </td>
   <td><a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/window.html">[Presentation]</a>
<p>
<a href="https://pandas.pydata.org/pandas-docs/stable/user_guide/window.html">Windowing, Categorical</a>
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.google.com/presentation/d/1vAzn6vGHKwt_jRIGj6bsP_ZCAIHXZITk/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation]</a>
<p>
<a href="https://docs.google.com/presentation/d/1vAzn6vGHKwt_jRIGj6bsP_ZCAIHXZITk/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">Numpy Arrays</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Pandas/Cheat_Sheet_Python_Pandas.pdf">[Pandas Cheat Sheet]</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Statistics/Notebook_Code_Along_Descriptive_Statistics_Structure.ipynb">[Notebook] Basic Statistical Concepts</a>
   </td>
   <td>[Notebook] EDA with plotting
   </td>
   <td>[Notebook]
<p>
Windowing, Categoricals
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Numpy/Numpy_Python_Cheat_Sheet.pdf">[Cheat Sheet] Numpy Arrays</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1IRgPY8aaoev3PTvEtoQ7q2yRx4zGzssv/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Pandas Joining, Grouping</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1PyidEaDkoAQGDRAQ5yEI_XjDtDh3A-g0/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Correlation of Numerical Features</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Data_Visualization/Matplotlib_Seaborn/Cheat_Sheet_Python_Matplotlib.pdf">[Cheat Sheet] Matplotlib</a>
   </td>
   <td>[Weekly Recap]
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Numpy/Notebook_Code_Along_Numpy_%20Structure.ipynb">[Code Along] Numpy</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Pandas/Notebook_Code_Along_Intro_To_Pandas_Healthcare%20For_All_Structure.ipynb">[Code Along] Pandas Joining, Grouping</a>
   </td>
   <td>[Activity] Correlation Matrix
   </td>
   <td>[Activity] Plotting
   </td>
   <td>[Weekly Retro]
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Pandas/Labs/Health_Care_For_All_Case_Study/Health_Care_for_All_Case_Study.md">[Healthcare For All Case Study]</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/tree/main/Class%20Materials/Pandas/Labs/Customer_Analysis_Case_Study">[Lab] Customer Analysis Case Study</a>
   </td>
   <td>[Activity] Grouping, Cleaning using Pandas Health Care For All Case Study 
   </td>
   <td>[Lab] EDA
   </td>
   <td>Kahoot*
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Pandas/Labs/Health_Care_For_All_Case_Study/Activities.md">[Lab] Healthcare for All Excel,Sheets</a>
   </td>
   <td>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Pandas/Labs/Customer_Analysis_Case_Study/Activities.md">[Lab] Customer Analysis</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.google.com/presentation/d/1kXw7mTOx232pkNJ0yXUCymgI9wLpXR5b/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Intro to Pandas</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Numpy/Labs/100_Numpy_exercises_with_hints.md">[Lab] Numpy Arrays</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td colspan="5" ><strong>Week 1</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Day 1</strong>
   </td>
   <td><strong>Day 2</strong>
   </td>
   <td><strong>Day 3</strong>
   </td>
   <td><strong>Day 4</strong>
   </td>
   <td><strong>Day 5</strong>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Command_Line/MAC%20Command%20Line%20CheatSheet.pdf">[Cheat Sheet] Mac Command</a>
<p>
<a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Command_Line/Windows%20Command%20Prompt%20Cheatsheet.pdf">[Cheat Sheet] Windows Command Line</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1egDiBylb77aqrLthgC3NaJ1YiJ6BZw1W/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Conda</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/17QFXLTEBHB1B3ytR-fjgEeF-W75tr9a2/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Python Functions</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1i0KOQG3RlQze9e7WUY_1rrc_mpsbyech/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Intro to Data Analysis</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1KQ7A-3THjig6wYmzy7JYfli3fnbB80nY/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Python Map, Filter, Reduce</a>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Command_Line/Activities/command_line_exercise.md">[Activity] Command Line</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Conda/%5BCheat%20Sheet%5D%20Conda_Cheatsheet.pdf">[Cheat Sheet] Conda Cheat Sheet</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Code_Along_Python_Functions.ipynb">[Notebook] Python Functions</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/17r2eSMW6qddFppf-GjuG-X4ldtZMs1gO/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Data Analysis Process</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Code_Along_Map_Filter_Reduce.ipynb">[Notebook] Python Map, Filter, Reduce</a>
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.google.com/presentation/d/1emti-9IkUK-fZUG3GoMyJ4mMXoMJG5zc/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Git Concepts</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1TlfVND7l8lLvJeW1TubloDG9P_Z0t5T0/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Python Object Types</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1NWZOIxhpjZS-VfBY2dPzo3JTr8izgQpR/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Programming Tips</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Data_Analysis_Intro/Readme.md">[Extra] Data Analysis</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1DUqpLwKqWRwVw7qKQ95ijDy39DPmdfeV/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Python Lists Comprehension</a>
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.google.com/presentation/d/12sATaHIireWiTPSmB46nHkrmyTbp7tOx/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Git Commands</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Code_Along_Python_Object_Types.ipynb">[Notebook] Python Object Types</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1sC-IOCVcIfMnFAbyPzHwjy_VDivEOuC2/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Programming Practices</a>
   </td>
   <td>[Activity] Data Analysis
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Code_Along_List_Comprehensions.ipynb">[Notebook] Python Lists Comprehension</a>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Git_GitHub/%5BCheat%20Sheet%5D%20Git_Cheat_Sheet_Education.pdf">[Cheat Sheet] Git Cheat Sheet</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Conda/Activities/Conda_Activity_environments.md">[Activity] Conda Environment</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Programming_Tips/Readme.md">[Extra] Programming Useful Resources</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1Duu10NP6eHDuo23cIYd4jU4MZVDbe0WY/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Python, Error Handling</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Labs/Lists%20Comprehensions/Lab_Python_List_Comprehension.ipynb">[Lab] Lab | Python Lists Comprehension</a>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Git_GitHub/Readme.md">[Extra] Git Extra Resources</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/tree/main/Class%20Materials/Python_Basics/Labs/Tuple_Sets_Dicts">[Lab] Lab | Python Sets, Tuples, Dicts</a>
   </td>
   <td><a href="https://docs.google.com/presentation/d/1ELYBx8TnVT2ISwqiWwbVWbdpxohL6634/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Python String Operations</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Code_Along_Error_Handling_Structure.ipynb">[Notebook] Python, Error Handling</a>
   </td>
   <td>[Lab] Lab | Prework Review
   </td>
  </tr>
  <tr>
   <td><a href="https://docs.google.com/presentation/d/1QxThJeuCdR8fd34tQ3JHCpWb2pOOsfrm/edit?usp=sharing&ouid=108298089999640278508&rtpof=true&sd=true">[Presentation] Jupyter Notebooks</a>
   </td>
   <td>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Code_Along%20_Python_String_Operations.ipynb">[Notebook] Python String Operations</a>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Labs/Error_Handling/Lab_Python_Error_Handling.ipynb">[Lab] Lab | Python Error Handling</a>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Jupyter_Notebook/markdown-cheat-sheet.md">[Cheat sheet] Markdown Cheat Sheet</a>
   </td>
   <td>
   </td>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Python_Basics/Labs/Python_Strings/LAB_Notebook_Python_Strings.ipynb">[Lab] Lab | Python Strings</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Jupyter_Notebook/Readme.md">[Extra] Jupyter Notebook Extra Resources</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/tree/main/Class%20Materials/Git_GitHub/Labs">[LAB] Lab | Git</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Jupyter_Notebook/Labs/lab_Juypter_Notebook.md">[LAB] Lab | Jupyter Notebook</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/raafat-hantoush/IH_RH_DA_FT_AUG_2021/blob/main/Class%20Materials/Command_Line/Labs/Lab-Bash.md">[LAB] (Optional) Lab | Bash</a>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>
