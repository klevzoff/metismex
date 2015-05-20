MetisMex
========

Warning: The basic routines of metis work now. Further help documents will be added in the future.

This code works with the latest stable version of Metis (5.1.0, 2013-03-30).

The following instructions worked on Ubuntu (14.04 LTS) and
OSX 10.10 with Matlab installed.

### Compile on Ubuntu
---------

1. Install the latest version of 
  [metis](http://glaros.dtc.umn.edu/gkhome/metis/metis/overview).
  ```
  sudo apt-get install libmetis-dev
  ```

2. Download and compile MetisMex.
  ```
  git clone https://github.com/YingzhouLi/metismex.git
  cd metismex
  matlab -nojvm -r "make;quit"
  ```

3. Test MetisMex
  ```
  cd test
  matlab &
  >> test
  >> test_sparse
  ```

### Compile on Mac
---------

1. Install the latest version of 
  [metis](http://glaros.dtc.umn.edu/gkhome/metis/metis/overview).
  ```
  brew install metis
  ```

2. Download and compile MetisMex.
  ```
  git clone https://github.com/YingzhouLi/metismex.git
  cd metismex
  matlab -nojvm -r "make;quit"
  ```

3. Test MetisMex
  ```
  cd test
  matlab &
  >> test
  >> test_sparse
  ```
### Install on Ubuntu
---------

1. Install the latest version of 
  [metis](http://glaros.dtc.umn.edu/gkhome/metis/metis/overview).
  ```
  sudo apt-get install libmetis-dev
  ```

2. Download and compile MetisMex.
  ```
  git clone https://github.com/YingzhouLi/metismex.git
  cd metismex
  matlab -nojvm -r "make(1);quit"
  ```

### Install on Mac
---------

1. Install the latest version of 
  [metis](http://glaros.dtc.umn.edu/gkhome/metis/metis/overview).
  ```
  brew install metis
  ```

2. Download and compile MetisMex.
  ```
  git clone https://github.com/YingzhouLi/metismex.git
  cd metismex
  matlab -nojvm -r "make(1);quit"
  ```
  
### Acknowledgments
-------
Many thanks to [David Gleich](https://www.cs.purdue.edu/homes/dgleich/)
and [Robert Bridson](http://www.cs.ubc.ca/~rbridson/).
[Yingzhou Li](https://www.stanford.edu/people/yingzhouli)
implements this repository
after carefully exploring their previous work [metismex](https://github.com/dgleich/metismex)
and [metismex.c](http://www.cs.ubc.ca/~rbridson/download/metismex.c).
