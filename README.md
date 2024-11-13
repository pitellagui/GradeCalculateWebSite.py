# GradeCalculateWebSite.py

A website built in Python using the Streamlit library.

This website calculates your weighted average grade and tells you the score you need on a recovery test (specifically for UDESC students).

## How to use: 

- Download
- In the terminal:
```bash
pip install -r requirements.txt
streamlit run GradeCalculateWebSite.py
```
- Enjoy!

# How is the average grade calculated at UDESC?

- **Semester Grade (SG):**
  - If **SG ≥ 7.0** → Pass
  - If **SG < 7.0** → Final Exam (FE)

 When the student needs to take the Final Exam (FE), the Final Grade (FG) is calculated as:
 
- **Final Grade (FG)** calculation formula:

![Final Exam Formula](FinalExamFormula.png)

  - If **FG ≥ 5.0** → Pass
  - If **FG < 5.0** → Fail

## How to calculate the Minimum Grade needed to pass?
![Min Grade Formula](MinGradeFormula.png)

Where: 
- SG => Semestral Grade
- MG => Minimum Grade


