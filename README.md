# xampp_on_debian
In this repository you will learn how to install xampp on debian os.<br>
<h3>What is XAMPP ?</h3>
                 XAMPP,which stands for ( Cross-Platform,Apache,MySQL,PHP,and Perl ), is a free platform that allows developers to test their code locally on their own computers.
                 This provide you own web server at your home.<br>
 <h3>pre-requirements:</h3> 
 <ol> 
 <li>Debian os</li>
 <li>Helthy internet connection</li>
 <li>Linux user with root privileges<br></li>
 </ol>
 <h3>Download the XAMPP installer package:</h3>
 Visit the official XAMPP website <a href="https://www.apachefriends.org/download.html" target="_blank">click here---> Download XAMPP on linux</a> to download the appropriate      installer for your Linux     distribution.<br>
 <b>When you click on the installer link the popup window will appear as shown below in figure(1.0)</b><br><br>
 <em>figure(1.0)</em>

 ![Screenshot from 2024-05-07 20-43-52](https://github.com/cyber-fanatic/xampp_on_debian/assets/159928985/7202b05c-517e-4b0a-b946-a61b02dc2ff0)<br>
1) <h3>Change file permissions:</h3>
<b>Shown in figure(2.0)</b>
<ul>
  <li>Open the terminal and navigate to the directory containing the downloaded package.</li>
  <li>Execute the command sudo chmod  +x  xampp-linux-*-installer.run to make the installer executable.</li>
  <li>After changing the mode to +x(executable) the color of downloaded package will changed.</li>
</ul>
<em>figure(2.0)</em>

![Screenshot from 2024-05-07 21-10-28](https://github.com/cyber-fanatic/xampp_on_debian/assets/159928985/29b7ef35-750b-4852-9093-7e2d57aa1ab2)

2) <h3>Run the XAMPP installer: (Shown in figure(3.0))</h3>
<ul><li>Run the installer using the command sudo ./xampp-linux-*-installer.run.</li></ul>
<em>figure(3.0)</em>

![Screenshot from 2024-05-07 21-14-06](https://github.com/cyber-fanatic/xampp_on_debian/assets/159928985/f1942f2a-ce4f-46f1-a34d-fdf3de31eb66)

3) <h3>setup XAMPP: (shown in figure(4.0 and 4.0.1))</h3>
<ul><li>Configure the xampp by clicking on the <ins>Forward</ins> button.</li></ul>
<em>figure(4.0)</em>

![Screenshot from 2024-05-07 21-15-39](https://github.com/cyber-fanatic/xampp_on_debian/assets/159928985/c7233bff-a3db-4430-b163-8e486d72d949)

<h3>After completing the setup process you will see popup window like figure(4.0.1) below:</h3>
<ul><li>You can also start and stop the services accordingly.</li></ul>

![Screenshot from 2024-05-07 21-21-59](https://github.com/cyber-fanatic/xampp_on_debian/assets/159928985/992af932-42ac-4eec-9d1c-06337fd8b64a)

4) <h3>Start the XAMPP server: (shown in figure(5.0))</h3>
<ul>
  <li>After installation, start the server with sudo /opt/lampp/lampp start.</li>
  <li>/opt/lampp/ are the directorys in the linux where xampp stored by default.</li>
  <li>lampp stands for: <b>Linux,Apache,MySQL,Perl,Php</b></li>
</ul>
<em>figure(5.0)</em>

![Screenshot from 2024-05-07 21-33-59](https://github.com/cyber-fanatic/xampp_on_debian/assets/159928985/38c27ee9-485d-4e7a-8bbe-6413b1eb9f09)



   


 
 
