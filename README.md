# Music-Habits-vs-Grades-and-Stress-Levels
Utilized machine learning to understand the impact of music habits on STEM & Business majors' grades and stress levels.

## Project Overview 
- **Goal:** Identify how music listening habits affect stress levels and GPA of STEM & Business majors
- **Approach:** Utilize machine learning techniques such as K-Means Clustering and Random Forests to uncover meaningful patterns between music listening habits, student performance, 
                and stress levels
- **Datasets:**
    1. Students_Grading_Dataset (5,000 records), includes real academic performance data from a private learning provider. Key attributes include age, attendance, major, total scores, 
       and stress levels.
    2. Music and Mental Health Survey (736 responses), capturing respondents’ preferred genres, music habits, study behaviors, and self-reported mental health indicators (e.g., 
       anxiety, depression, insomnia).

## Tools Used
- Python, Scikit-learn, Pandas, Scipy, Matplotlib, Seaborn, NumPy
- Google Colab

## Key Findings
1. Low Beats Per Minute (BPM) music is aassociateed with lower stress levels
   - Participants who primarily listened to music under 90 BPM reported signigicantly lower average stress scores.
   - This trend held across such as classical, ambient, lo-fi, and acoustic pop.

2. Moderate listening duration (~1 to 1.25 hours/day) is optimal
   - This listening range was linked to lower stress and higher average GPA, suggesting moderate music consumption supports focus and recovery.

3. High Beats Per Minute (BPM) music correlate with higher stress levels
   - Genres with high BPM (e.g., EDM, Trap, Heavy Metal) were more commonly reported among those with moderate to high stress levels and lower GPAs.
   - However, the effect may be context-dependent as some listeners in this category reported using high BPM music for exercise.

4. Beats Per Minute and Listening Duration are stronger predictors than genre
   - While genre had influence, the models showed that BPM and daily listening time were the strongest predictors of both stress and GPA, more so than genre or user demographics.
