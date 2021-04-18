# booking

Git
** Add Code ที่ต้องใช้ 
	git add --all

** ดูไฟล์ที่แก้ 
	git status

** Commit Local 
	git commit -am ""

** Pull จาก Server ลงมา 
	git pull --rebase

****** Start Marge ****** ** ถ้า marge ต้องแก้ไฟล์ก่อน
**ดูไฟล์ที่แก้ จะเป็นสีแดง git status
เป็นการ Add File ที่ Commit git add --all
**ดูไฟล์ที่แก้ จะเป็นสีเขียว git status
**Net Step rebase Code 
	git rebase --continue
(Loop เดิม จนกว่าจะหาย) 
****** End Marge ******

นำไฟล์ขึ้น Server git push

****** Stash *************
เก็บ code ไว้ก่อนเพื่อจะ pull rebase
Git stash
เอา stash ที่เราเก็บไว้กลับมา
Git stash pop 


