# MonodevelopModelBuilderEXT

Simple project to use automl and mlnet cli via monodevelop. This is just the first iteration. this project requires mono be installed, dotnet cli and mlnet cli. As well as monodevelop IDE. Instructions to install are below.

--to use: add the "modelBuilderApp" folder to home, and then install the monodevelop extension. 

--to install, open tools, click extensions and click install from file. select the MLNETMODELBUILDER.MLNETMODELBUILDER_1.0.mpack file and hit ok.

--once installed you can click on the edit menu, and then select Open Model Builder. that will open the Model Builder Applet.


NOTE+++++++++++++++++++++++++++++++++++++++++++++

when installing mlnet cli you need to use the following commands to set the environment variables. ubuntu 18.04 isnt setting them up right.

-- export PATH="$PATH:~/.dotnet/tools"

-- echo 'export PATH="$PATH:~/.dotnet/tools"' >> ~/.bashrc

+++++++++++++++++++++++++++++++++++++++++++++++++

INSTALL MONODEVELOP++++++++++++++++++++++++++++++

sudo apt install apt-transport-https dirmngr

sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF

echo "deb https://download.mono-project.com/repo/ubuntu vs-bionic main" | sudo tee /etc/apt/sources.list.d/mono-official-vs.list

sudo apt update

sudo apt-get install monodevelop

+++++++++++++++++++++++++++++++++++++++++++++++++++++
