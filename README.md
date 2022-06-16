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
![圖片](https://user-images.githubusercontent.com/58076095/174140542-236b1c74-3aee-44bc-a60e-31f3e9f157e0.png)
  
8.q  
![圖片](https://user-images.githubusercontent.com/58076095/174140603-36c35c57-62e7-4334-8e60-cca35e5f2044.png)
  
9.sudo ufw enable
![圖片](https://user-images.githubusercontent.com/58076095/174140654-550c7913-2c55-4191-92e4-aff878358a34.png)
  
10.sudo ufw allow 10000/tcp  
![圖片](https://user-images.githubusercontent.com/58076095/174140733-0537c991-12dd-4d98-be58-6df60f5e7beb.png)
  
11.sudo ufw reload  
![圖片](https://user-images.githubusercontent.com/58076095/174140786-05821f35-8560-4ea8-a72c-f2df958904d3.png)
  
12.sudo /usr/share/webmin/changepass.pl /etc/webmin root password  
![圖片](https://user-images.githubusercontent.com/58076095/174140889-04810b8f-19bc-4209-bfb7-d295822a0894.png)
  
13.ip addr  
![圖片](https://user-images.githubusercontent.com/58076095/174141003-7eeb3bf2-bf26-4552-b20a-9aca58e2f5ae.png)
  
14.Open browser and type https://server-IP:10000/ .  
![圖片](https://user-images.githubusercontent.com/58076095/174141087-103330a5-68d5-4847-8f01-7ac339ba43a1.png)
  
15.Click Advanced.  
![圖片](https://user-images.githubusercontent.com/58076095/174141624-55dbe6cc-7307-4198-8322-ff213d065531.png)
  
16.Click Proceed.  
![圖片](https://user-images.githubusercontent.com/58076095/174141733-e8de6ad7-0e3c-43c9-9b2e-867a05e93c3b.png)
  
17.Login.  
![圖片](https://user-images.githubusercontent.com/58076095/174141871-d5b3a1d9-6f3c-4e28-a125-25fe29121ca4.png)
  
18.Click Refresh Modules.  
![圖片](https://user-images.githubusercontent.com/58076095/174142028-68815ede-53d5-45ad-a223-f0f3bb114714.png)
  
