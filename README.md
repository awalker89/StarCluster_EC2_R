# StarCluster_EC2_R
Setting up StarCluster on Windows and running in Parallel with R and foreach


* Step 1 - Install Python 2.7

    https://www.python.org/downloads/

  and make sure python27 is added to the system PATH variable "c:\users\python27" can check this ath the command line with
  ```
  PATH
  ``` 



* Step 2 - Install Cygwin with ssh (OPTIONAL - openssh is under "net")

    https://cygwin.com/install.html
    ftp://ftp.perforce.com/perforce/tools/benchmarks/browse/doc/cygwin.html
    
    
* Step 3 - Install C++ compiler for Python 2.7

    http://aka.ms/vcpython27


* Step 4 - Install StarCluster
    
    at the command line enter
    ```
    pip install starcluster
    ```

* Create StarCluster config file

    at the command line enter
    ```
    start starcluster mycluster
    ```
    
    and then enter 2
    



 
