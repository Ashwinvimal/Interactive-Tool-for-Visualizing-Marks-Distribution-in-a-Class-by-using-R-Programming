# Interactive-Tool-for-Visualizing-Marks-Distribution-in-a-Class-by-using-R-Programming
Interactive Tool for Visualizing Marks Distribution is a powerful and user-friendly R Shiny application designed for educators to analyze and understand student performance with ease. The tool allows users to upload marks data in CSV or Excel format and instantly generates insightful statistics like mean, median, standard deviation, and percentiles. It also features a wide range of interactive visualizations, including histograms, bar charts, box plots, pie charts, and density plots, helping teachers and administrators identify patterns and trends in academic performance.
This application requires no coding knowledge and includes intuitive filters to drill down into student-wise or subject-wise data. It also supports exporting full performance reports in both PDF and HTML formats — ideal for meetings, records, or sharing. Built using R, Shiny, ggplot2, plotly, and other core libraries, the project emphasizes simplicity, interactivity, and real-time insight into classroom data.
Whether you're handling a small class or large batches, this tool makes marks analysis accurate, fast, and visually engaging.

📖 How to Use
Follow these steps to use the Interactive Tool for Visualizing Marks Distribution:

1.Prepare Your Data File

Format your student marks in a CSV or Excel file.

Make sure the file contains clearly labeled columns (e.g., Student Name, Subject, Marks, etc.).

2.Run the Application

Open R or RStudio.

Install required packages (if not already installed):

install.packages(c("shiny", "dplyr", "ggplot2", "plotly", "readr", "readxl"))
Run the app:

shiny::runApp("path/to/your/app.R")
The app will open in your browser at http://localhost:3838/.

3.Upload Marks File

Click the "Upload" button in the app.

Select your marks file (CSV or Excel).

The app will automatically process and display the data.

4.Explore the Dashboard

Use filters to select subjects, individual students, or mark ranges.

View charts like histograms, bar charts, box plots, and pie charts.

See key statistics: mean, median, total, standard deviation, etc.

5.Download Reports

Click the “Download Report” button to save a summary as a PDF or HTML file.

Share with your colleagues or keep for documentation.

Repeat as Needed

You can upload new files anytime and instantly get updated visualizations.
