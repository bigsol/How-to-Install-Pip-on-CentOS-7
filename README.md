How to Install Pip on CentOS 7

nstalling pip on CentOS
To install pip on your CentOS machine, follow these steps:

1. Add the EPEL Repository 
* Pip is not available in CentOS 7 core repositories. To install pip we need to enable the EPEL repository :
sudo yum install epel-release

2. Install pip
Once the EPEL repository is enabled we can install pip and all of its dependencies with the following command:
sudo yum install python-pip

3. Verify Pip installation
pip --version

Install development tools
Development tools are required for building Python modules, you can install them with:
sudo yum install python-devel
sudo yum groupinstall 'development tools'


