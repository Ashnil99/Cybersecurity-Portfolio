# 01. Linux Basic Commands <br>

![image](https://github.com/user-attachments/assets/b709ef02-af2f-49ba-9c6d-88e26325f1c0)

TR - Görseldeki rakamlarla belirtilmiş olan komutlar sırasıyla:

1 mkdir: "logs" isimli bir dosya dizini oluşturur <br>
2 rmdir: "temp" dizinini siler <br>
3 mv: "Q3patches.txt" not defretini /home/analyst/reports/ dosya dizinine taşır<br>
4 rm: "tempnotes.txt" not defterini siler<br>
5 touch: "tasks.txt" dosyasını oluşturur<br>
6 nano: not defterinin içeriğine ulaşmamızı sağlar.<br>

EN - The numbers next to the commands on the picture do the following:

1 mkdir: creates a directory named "logs" <br>
2 rmdir: deletes the directory called "temp"  <br>
3 mv: moves "Q3patches.txt" to the /home/analyst/reports/ directory<br>
4 rm: deletes the file "tempnotes.txt"<br>
5 touch: creates the file "tasks.txt"<br>
6 nano: allows us to get inside the text editor.<br>

# 02. Linux Commands for Managing Directories<br>
![image](https://github.com/user-attachments/assets/cf330881-b229-4b07-99fd-e9f4ac67ab8a)

Linux komutlarını öğrenmek zor değil:

Görseldeki rakamlarla belirtilmiş olan komutlar sırasıyla:

1 mkdir: "logs" isimli bir dosya dizini oluşturur
2 rmdir: "temp" dizinini siler
3 mv: "Q3patches.txt" not defretini /home/analyst/reports/ dosya dizinine taşır
4 rm: "tempnotes.txt" not defterini siler
5 touch: "tasks.txt" dosyasını oluşturur
6 nano: not defterinin içeriğine ulaşmamızı sağlar.

EN- It is not difficult to learn Linux commands:

The numbers next to the commands on the picture do the following:

1 mkdir: creates a directory named "logs"
2 rmdir: deletes the directory called "temp"
3 mv: moves "Q3patches.txt" to the /home/analyst/reports/ directory
4 rm: deletes the file "tempnotes.txt"
5 touch: creates the file "tasks.txt"
6 nano: allows us to get inside the text editor.

# 03. Linux Commands for Creating Users and Management of Privileges<br>
![image](https://github.com/user-attachments/assets/97ab3c81-ffd9-43dc-8685-759696315120)

Linux Bash komut satırında bir şirketin çalışanlarını düzenlemek, grup oluşturmak, gruba yeni üye eklemek ve onların şirketteki dosyalara erişebilmek üzere olan yetkilerini kontrol etmek için sudo komutları kullanılır.

1- researcher9 isimli kullanıcıyı sisteme eklemek için bir komut girin.
2- usermod komutunu kullanarak ve -g eklentisini de yazarak researcher9 kullanıcısını research_team grubuna, o grubu öncelikli grup olarak alacak şekilde ekleyin.
3- chown komutu kullanarak researcher9'un /home/researcher2/projects/project_r.txt dosyasına tam erişim sağlayacak şekilde ayarlayın.
4- usermod komutunu -a ve -G seçenekleriyle, researcher9'un sales_team grubunu ikincil grup olarak alacak şekilde kullanın.
5- researcher9 kullanıcısını silin.
6- Daha önceden researcher9 un içinde olduğu grubu da silin.

EN - In Linux Bash Shell, sudo commands are widely used to create a group, add new group members, and control their privileges in a company's internal file system.

1-Write a command to add a user called researcher9 to the system.
2-Use the usermod command and -g option to add researcher9 to the research_team group as their primary group.
3-Use the chown command to make researcher9 the owner of /home/researcher2/projects/project_r.txt.
4-Use the usermod command with the -a and -G options to add researcher9 to the sales_team group as a secondary group.
5-Run a command to delete researcher9 from the system.
6-Run the command to delete the researcher9 group that is no longer required.
