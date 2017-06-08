cmake_minimum_required(VERSION 2.8.3)
project(python-watchdog)

find_package(catkin REQUIRED COMPONENTS
             catkin_pip
  )

catkin_pip_package(pyhton-watchdog)

## Add folders to be run by python nosetests
#catkin_add_nosetests(tests)
