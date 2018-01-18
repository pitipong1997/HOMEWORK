# homework
echo "# homework" >> HOMEWORK.md // คำสั่งนี้คือการเขียนข้อความ homework ไปยังไฟล์ HOMEWORK.md

git init // คำสั่งนี้จะสร้างแฟ้มข้อมูลย่อยชื่อ .git ซึ่งเก็บแฟ้มโครงสร้างของ Git repository เปล่า ๆ ที่ยังไม่มีเนื้อหาใด ในขั้นตอนนี้แฟ้มที่อยู่ในโปรเจคของคุณจะยังไม่ถูก track โดย Git

git add HOMEWORK.md // คือการเพิ่มไฟล์ HOMEWORK.md 

git status // คือการเช็คสถานะของ git

git config --global user.email "5835512033@psu.ac.th" // คือการเชื่อมต่อไปยังอีเมลล์ของผู้ใช้

git config --global user.name "pitipong1997" // คือการเชื่อมต่อไปยังชื่อผู้ใช้

git commit -m "first commit" // ใช้เพื่อบันทึกการเปลี่ยนเเปลง
		
git remote add origin https://github.com/pitipong1997/homework.git // เป็นการเพิ่มไฟล์ไปยัง git

git remote -v

git push -u origin master // เป็นการอัพไฟล์ที่เขียนไว้ขึ้นไปยัง github

จากนั้นจะให้ใส่ username password เพื่อเข้าถึง github ที่จะอัพโหลด
