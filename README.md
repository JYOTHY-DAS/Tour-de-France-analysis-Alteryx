# Tour de France Data Analysis with Alteryx

This project analyzes historical Tour de France data using Alteryx Designer. It involves data cleansing, transformation, time parsing, and performance ranking of riders across different years.

## 📁 Datasets Used
- `tdf_winners.xlsx`: Information about Tour de France winners and their finish times.
- `tdf_finishers.xlsx`: Complete list of finishers and their time margins.
- `tdf_stages.xlsx`: Stage-level data for each tour.
- `tdf_tours.xlsx`: Tour metadata including year, starting and ending date, starters and finishers.

## 📊 Key Tasks Performed
- Cleansed input data.
- Cleaned inconsistent time formats in rider finishing times.  
- Extracted hours, minutes, and seconds using Regex. 
- Calculated actual finishing times in seconds.  
- Identified winner times and computed margins.  
- Joined datasets on Year and Tour_ID for unified analysis.  
- Sorted riders by performance.  

## 📁 Project Structure
```
Tour_de_France/
├── Input_data/
│ ├── tdf_finishers.xlsx
│ ├── tdf_stages.xlsx
│ ├── tdf_tours.xlsx
│ └── tdf_winners.xlsx
├── Documentation/
│ ├── Tour_de_France_Questions.pdf
│ ├── Tour_de_France_Info.pptx
├── Workflow/
│   └── Tour_de_France.yxmd
└── README.md
└── LICENSE
```
---
## 🛠️ Tools Used
- **Alteryx Designer**
  - Input Tool
  - Data Cleansing
  - Formula Tool
  - Regex Tool
  - Multi-Row Formula
  - Sort, Join, and Filter tools

## 📎 How to Use

1. Open `Tour_de_France.yxmd` in Alteryx Designer.  
2. Ensure the input files from the `Input/` folder are correctly referenced in the workflow (update paths if needed).  
3. Choose an output folder on your system (update the Output Data tools accordingly).  
4. Run the workflow.  
5. Review the results in your designated output folder.

## 📜 License

- This project is for educational purposes. You may modify and share with credit.
