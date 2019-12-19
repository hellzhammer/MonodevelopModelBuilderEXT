# ModelBuilderAndDataConverter

----- I have only tested this on ubuntu 18.04. -------

-This app will build your ml.net models.

-Uses automl and microsoft.ml.

-You will need to install .net core / mlnet before running this.
Dotnet Core -- https://dotnet.microsoft.com/download
mlnet cli -- dotnet tool install -g mlnet

-uses .csv/.tsv files. 

-all of the command line params can be set via gui tool.

-starts build process in a seperate console allowing you to train multiple instances.

++++++++ADDED CONVERT JSON TO TSV++++++++++++++++++

--click "Convert Json", 
-- fill out form,
-- press convert,
-- produces .tsv file in specified output folder.

NOTE+++++++++++++++++++++++++++++++++++++++++++++

when installing mlnet cli you need to use the following commands to set the environment variables. 
ubuntu 18.04 isnt setting them up right.

-- export PATH="$PATH:~/.dotnet/tools"

-- echo 'export PATH="$PATH:~/.dotnet/tools"' >> ~/.bashrc

+++++++++++++++++++++++++++++++++++++++++++++++++
