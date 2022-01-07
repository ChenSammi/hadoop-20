BUILD on Mac
========================================================================
1. Install Ant
   a. First install brew if it's not installed
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
   b. Install Ant
   brew install ant


2. Build tar package
   ant clean // clean all previous build files
   ant -Djava8.home="your java8 home path" tar


3. Tar package 
   After the build succeed, the tar package is "hadoop-0.20.tar.gz" under build directory. Use this tar package to install Hadoop cluster and RaidNode. 

 
   
