How to Install Pip on CentOS 7<br>
<br>
installing pip on CentOS<br>
To install pip on your CentOS machine, follow these steps:<br>
<br>
1. Add the EPEL Repository <br>
* Pip is not available in CentOS 7 core repositories. To install pip we need to enable the EPEL repository :<br>
<br>
sudo yum install epel-release<br>
<br>
2. Install pip<br>
Once the EPEL repository is enabled we can install pip and all of its dependencies with the following command:<br>
<br>
sudo yum install python-pip<br>
<br>
3. Verify Pip installation<br>
<br>
pip --version<br>
<br>
Install development tools<br>
Development tools are required for building Python modules, you can install them with:<br>
<br>sudo yum install python-devel<br>
<br>sudo yum groupinstall 'development tools'<br>
<br>


