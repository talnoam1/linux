# echo - הד
כל מה שנרשום ליד הפקודה - יוחזר
```
echo hi
hi
```
הדפסת ערך של משתנה
``` 
b=4
echo $b
```
# date - 
פקודה זו תדפיס את התאריך הנוכחי למסך
```
date
```
# ls 
מראה את כל מה שבתקייה הנוכחית
```
ls
```
# ls -l
מראה גם את ההרשאות של הקבצים
* Directory - תיקייה - יתחיל ב-d
* - הכוונה שזהו קובץ ולא תקייה
```
r - read
w - write
x - execute - להריץ

1 - rwx - for writer
2 - rwx - for group
3 - rwx - for everyone else

```
# test - יוצר קובץ חדש אם לא קיים, ואם קיים - מכניס לתוכו
```
test a.bash
```

# permission denied - ההרשאה נדחתה
אין לנו אפשרות להריץ קובץ זה, מכיון שאין לנו הרשאות מתאימות

# chmod - change mod - שינוי הרשאות לקובץ
```
chmod 777 a.bash
```

# cat - מראה את תוכן הקובץ
```
cat a.bash
```
# nano - עריכת הקובץ
```
nano a.bash
```
# ls -a
יראה לנו גם את הקבצים הנסתרים
איך נדע אם קובץ הוא נסתר? אם הוא מתחיל בנקודה

# rm a.bash - ימחוק את הקובץ

# Exit code - קוד היציאה
אם קוד היציאה הוא 0- זה אומר שהפקודה שלמעלה הצליחה
```
echo $?
0
```
# cp - copy - להעתיק
```
cp noam1.txt moam2.txt
```

# sudo - super user
משתמש הכי ראשי, שיש לו את כל ההרשאות במחשב

```
sudo -i
```
# wc - נותן פרטים על הקובץ
```
wc noam.bash
```
1. wc -l noam.bash - שורות
2. wc -w noam.bash - מילים
3. wc -c noam.bash - תווים



