# <center>KNES 381 Final Project💻</center> 

### By: Valeria Zaldivar (30202724) | For: Dr. John Holash 

**This website provides a rundown on kinesiology-based data analysis and sport movement evaluation using Excel, Python, and Darthfish.**

*Website outline:*
<p>1. An Excel spreadsheet and graph analyzing athlete data.</p>
<p>2. A Python program interpreting metabolic data such as VO₂ data.</p> 
<p>3. A biomechanical video analysis on squat kinematics.</p>
 

## 📊**Excel Spreadsheet**
**Figure 1** displays a clustered 2-D column graph demonstrating a linear relationship between athletes' physiological improvement and their years of experience.

**Figure 1**
![Athlete Data](/images/Picture1.png)

*You can also download this graph by clicking on the following links:*
- 🗃️[KNES 381_Excel Graph.xls](https://github.com/valeria-zaldivar/Knes381/blob/91a3d47460d3c12f9df26af1fbf71bacc979eb22/ExcelGraphics_Final%20Project_github.xls)
- 🗃️[KNES 381_Excel Graph.xlt](https://github.com/valeria-zaldivar/Knes381/blob/1d202fbea56de42ff8e09c70ed5e616017d18c85/ExcelGraphics_FinalProject_github.xlt)

**Figure 2** illustrates an analysis on athletes' *recovery, workload, and BMI* derived from pre-existing data.

**Figure 2**
![Excel Logo](https://raw.githubusercontent.com/valeria-zaldivar/Knes381/9d40e74ba4fed9eb7c333b231d482936faec88ee/excel.png)

*Key formulas used to determine levels of recovery, workload, and BMI:*
+ **Recovery:**
  - =IF(AND([@[Injury_Risk_Pct]]>10,[@[Recovery_Hours_Day]]<6), "Alert", "OK")
- **Workload:**
  - =IF([@[Training_Hours_Week]]>AVERAGEIFS([Training_Hours_Week],[Age],">"&[@Age]-15)*1.25,"High Workload","OK")
- **BMI Classification:**
  - =IF([@[BMI ]]<19.6, "Underweight", IF([@[BMI ]]<25, "Normal", IF([@[BMI ]]<30, "Overweight", IF([@[BMI ]]>=30, "Obese" ))))

*Click on the links below to access the Excel sheets directly:*
- 📁[KNES 381_Excel Data_github.csv](https://github.com/user-attachments/files/19679017/Excel.data_final.project_github.csv) 
- 📁[KNES 381_Excel Data.xltxl](https://github.com/valeria-zaldivar/Knes381/blob/771bf3447eaa43f3e5896032929fb5963431ce4a/images/Excel%20data_final%20project%20(1).xltx)
- 📁[KNES 381_Excel Data.xls](https://github.com/valeria-zaldivar/Knes381/blob/6ca23d051b8fa11c9ce46a8e81f3c83c57496de9/ExcelAthleteData_Final%20Project_github%20(1).xls)


## 🐍**Python Program**

**Figure 3** uses Python to evaluate VO₂, FECO₂, and VCO₂ data from *Subject_1432.*

**Figure 3**
![Kaggle Logo](https://raw.githubusercontent.com/valeria-zaldivar/Knes381/9d40e74ba4fed9eb7c333b231d482936faec88ee/kaggle.png)

*Click on the link below to access the Python code to go more in depth into the process behind Figure 3:*
- 📔[KNES 381_Python Assignment.ipynb](https://github.com/valeria-zaldivar/Knes381/blob/b3714e8d70bb99c537d17a93164c497e7c42fa1f/KNES%20381_Python%20Assignment.ipynb#L1)

- 🔗[View Kaggle Notebook](https://www.kaggle.com/code/valeriarzaldivar/knes-381-python-assignment) 

## 📹**Video Analysis** 
<p>Through the use of Dartfish, a biomechanical analysis was carried on to observe knee flexion and posture when performing a squat. A brief overview can be seen in the pictures below.</p>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 10px; margin: 20px 0;">
 <img src="https://raw.githubusercontent.com/valeria-zaldivar/Knes381/640bd7ee456486bac43175793d5bb3b182df094e/1.png" alt="Step 1" style="width: 23%; min-width: 150px;">
 <img src="https://raw.githubusercontent.com/valeria-zaldivar/Knes381/640bd7ee456486bac43175793d5bb3b182df094e/2.png" alt="Step 2" style="width: 23%; min-width: 150px;">
 <img src="https://raw.githubusercontent.com/valeria-zaldivar/Knes381/640bd7ee456486bac43175793d5bb3b182df094e/3.png" style="width: 23%; min-width: 150px;">
 <img src="https://raw.githubusercontent.com/valeria-zaldivar/Knes381/640bd7ee456486bac43175793d5bb3b182df094e/4.png" alt="Step 4" style="width: 23%; min-width: 150px;">
 </div>

*Click on the link below to access the full video:*
- 🏋️‍♂️[KNES 381 Video Analysis](https://github.com/valeria-zaldivar/Knes381/blob/b27af5a37442f4d409352bd06ff24a39dd261aa4/Video%20Analysis.mov)







