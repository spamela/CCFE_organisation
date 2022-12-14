# Omniverse logs
Working Logs and Wikis for work related to Omniverse.

# Omniverse installation
If installing on Windows, make sure that Paraview is not running when you install the Omniverse paraview connector.<br/>
If installing on Ubuntu, be careful with the openssl libraries, if they are not present, the Omniverse Paraview connector will install successfully, but it will not work in Paraview. The best way to see this is to try and install the connector by commandline instead, for which instructions can be found at https://docs.omniverse.nvidia.com/con_connect/con_connect/paraview.html <br/>
This gave an error regarding openssl, but installing the standard Ubuntu ssl packages didn't resolve it and I had to manually download the library and install it: <br/>
wget "http://security.ubuntu.com/ubuntu/pool/main/o/openssl1.0/libssl1.0-dev_1.0.2n-1ubuntu5.10_amd64.deb" <br/>
sudo dpkg -i libssl1.0-dev_1.0.2n-1ubuntu5.10_amd64.deb <br/>

Always remember to install the Nvidia drivers obviously

# Viewing CAD files in Omniverse
There is a function to convert .obj to .usd inside Create, which seems to be the most straight-forward
