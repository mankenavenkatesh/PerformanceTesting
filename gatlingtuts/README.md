Gatling

What is the problem solved by gatling?
1) Gatling is a load testing framework.
2) it is based on scala, akka and netty.


How to install and run?
1) from http://gatling.io/download/ download gantling bundle zip. 
2) it can also be used as part of maven build. http://gatling.io/download/#buildtool
3) extract zip. go to bin folder. run gataling.sh script file.
4) above script file will run all the tests.

Quickstat gatling
1) http://gatling.io/docs/current/quickstart/


Location of tests
1)  In the zip, go to user-files
2) it will contain all the tests in scala files.


Recording the requests
1) run ./recorder.sh inside zip bin folder.
2) Inside recorder, just click start.(do any changes if required.) listening port is 8000 on localhost.
3) once started, go to crome/settings/advancedsettings/proxysettings. Add web proxy. localhost:8000.
4) once proxy is added, refresh http://www.bbc.com/.
5) in recorder you should see requests getting recorded.
6) It will create a scala script file as well in the user-files/simulations directory.
7) these scripts are examples of how to write scala gatling scripts.

Website
http://gatling.io/


References
https://www.youtube.com/watch?v=fqP6PTUdtkY&index=1&list=PLd4gvNaNZ4T3NCWsv3zwHYlLGtr9s1-Fz
