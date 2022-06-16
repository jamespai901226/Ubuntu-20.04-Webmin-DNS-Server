# Ubuntu-20.04-Webmin-DNS-Server
1.Install Ubuntu 20.04 Server, login, and open terminal.  
2.sudo apt update && sudo apt upgrade
![圖片](https://user-images.githubusercontent.com/58076095/174140002-b483b47c-9fe0-4a58-8364-dca9153f64ef.png)
  
3.sudo apt install software-properties-common apt-transport-https  
![圖片](https://user-images.githubusercontent.com/58076095/174140148-e41846c1-c0ff-40e8-8a65-1b365878be27.png)
  
4.sudo wget -q http://www.webmin.com/jcameron-key.asc -O- | sudo apt-key add -  
![圖片](https://user-images.githubusercontent.com/58076095/174140268-447e2115-16a9-47ff-b63a-57693dbfb440.png)
  
5.sudo add-apt-repository "deb [arch=amd64] http://download.webmin.com/download/rpository sarge contrib"  
![圖片](https://user-images.githubusercontent.com/58076095/174140370-ebd68908-a641-4886-867c-36bc11fa99c8.png)
  
6.sudo apt install webmin  
![圖片](https://user-images.githubusercontent.com/58076095/174140448-6383ad49-f211-474a-9084-6ab30cbcd10d.png)
  
7.sudo systemctl status webmin
