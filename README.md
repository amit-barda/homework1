# homework1
amit@DESKTOP-EN1P8AI MINGW64 ~
$ cd ~/Desktop

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop
$ mkdir homework

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop
$ cd homework

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework
$
נגשתי לשולחן עבודה ויצרתי תקייה בשם HOMEWORK ולאחר מכן נגשתי לתקייה
לאחר מכן התחלתי בתהליך עבודה על מנת שהגיט יעקוב אחרי הפרויקט שלי ולצורך כך השתמשתי בפקודהGIT INIT 
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework
$ git init
Initialized empty Git repository in C:/Users/amit/Desktop/homework/.git/

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git add .
warning: in the working copy of '1.txt', LF will be replaced by CRLF the next time Git touches it
אחרי שעשיתי GIT INIT כדאי שהגיט יעקב אחרי הקובץ שלי השתמשתי בפקודה GIT ADD . הייתי יכול באותה דרך לרשום את השם של הקובץ וזה עוקב אך מכיוון שיש לי רק קובץ אחד בחרתי להגיד להגיד לגיט לעקוב אחרי כל מה שיש בתקיה 
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git cmmit -m "homework step1"
git: 'cmmit' is not a git command. See 'git --help'.

The most similar command is
        commit

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git commit -m "homework step1"
[master (root-commit) 21b0f45] homework step1
 1 file changed, 1 insertion(+)
 create mode 100644 1.txt

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git status
On branch master
nothing to commit, working tree clean
לאחר כל התהליך הגיט בקש ממני לתת קומנט ל"צעד" שעשיתי עד עכשיו ולאחר שנתתי קומנט רציתי לבדוק את עצמי שהכל תקין ושהגיט עוקב אחר הקובץ שלי לצורך כך השתמשתי בפקודה GIT STATUS שמראה אחר מה הגיט עוקב או לא עוקב בתיקייה וראיתי שהכל מעודכן ותקין
שלב השני שהתבקש לעשות הוא לצור עוד "צעד" ולאחר מכין לעלות אותו לגיטHAB   
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ echo "is not hard" >> 1.txt

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ cat 1.txt
homework
is not hard
מה שאפשר לראות שעשיתי פה זה שהוספתי עוד טקסט לקובץ הקיים ובדקתי מה יש לי בתוך הקובץ בעזרת הפקודה CAT המציגה את תוכלת הקובץ   
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git add .
warning: in the working copy of '1.txt', LF will be replaced by CRLF the next time Git touches it

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git commit -m "homework step2"
[master 3616999] homework step2
 1 file changed, 1 insertion(+)
לאחר מכן אמרתי לגיט לעדכן את הקובץ בעזרת GIT ADD ורציתי שזה ישמר בתור צעד נוסף אז השתמשתי בפקודה GIT COMMIT ונתתי שם חדש לצעד הזה 
amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git status
On branch master
nothing to commit, working tree clean

amit@DESKTOP-EN1P8AI MINGW64 ~/Desktop/homework (master)
$ git log
commit 3616999152d0ade0104680f757ec9d5de28c79e1 (HEAD -> master)
Author: amit <amit11barda@gmailcom>
Date:   Fri Mar 24 19:31:40 2023 +0300

    homework step2

commit 21b0f451050ee1e2ae8e535340910527ccd3c552
Author: amit <amit11barda@gmailcom>
Date:   Fri Mar 24 19:05:27 2023 +0300

    homework step1
עכשיו שוב בדקתי שהכל מעודכן בתיקיה שלי בעזרת GIT STATUS  ורציתי לראות את תהליך העבודה שלי עד עכשיו אז השתמשתי בפוקדה GIT LOG אשר מראה לי את קומטים שנשמרו עד לרגע הנוכחי בעבודה
אחרי שיצריתי שתי "צעדים" הדבר האחרון שנשאר לי לעשות בשביל לסיים עם המטלה הוא לעלות הכל לגיטHAB 

