# HMC

This project demonstrates Random Walk vs Hamiltonian Monte Carlo
using an interactive website and supporting visualizations.

## Live Demo
👉 [Click here](https://yaeliavni.github.io/HMC/HMC.html) to open the interactive lab.

## Mode Selection
Basic Comparison: מראה את ההשוואה הכללית בין היעילות של הילוך אקראי ל-HMC.
Advanced Analysis: מספק ניתוח סטטיסטי מפורט יותר, כולל מדדים מתקדמים של ביצועים.
Treasure Hunt Game- אנלוגיה לאלגוריתם: מצב תחרותי שבו האלגוריתם הראשון שמגיע ל-10 "אוצרות" (אזורים בעלי הסתברות גבוהה) מנצח. 
HMC Mind Reader: מציג את תהליך החשיבה של HMC בזמן אמת, כולל חישובי גרדיאנט, הצעות מסלול והחלטות קבלה.

## Controls
הגדרות אלו מאפשרות לך לשלוט על פרמטרים שונים באלגוריתמים:
Sampling Speed: קובע את מהירות האנימציה, מ-1x (איטי) עד 20x (מהיר).
Random Walk Step Size: קובע את המרחק שהאלגוריתם של הילוך אקראי נע בכל צעד. צעדים גדולים יכולים לחקור שטח רחב יותר במהירות אך עלולים לפספס אזורים חשובים.
HMC Trajectory Length: קובע כמה זמן HMC "מחשב" את המסלול שלו לפני כל קבלת החלטה. מסלולים ארוכים יותר משתמשים ביותר מידע.
Distribution Type: מאפשר לך לבחור את הצורה של ההתפלגות הסטטיסטית שאתה רוצה לדגום ממנה:
Multiple Peaks : התפלגות עם כמה אזורים של הסתברות גבוהה.
Single Peak: התפלגות פשוטה עם אזור יחיד ומוגדר של הסתברות גבוהה.
Valley Shape : התפלגות מורכבת עם אזור צר וארוך של הסתברות גבוהה.
Ring Shape : התפלגות עם צורה מעגלית של הסתברות גבוהה.


