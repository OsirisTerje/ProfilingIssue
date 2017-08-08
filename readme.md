# Profiling issue with NUnit 3.7/3.8 adapter and Visual Studio Test Explorer

## Environment

Visual Studio 2017, latest build 15.2.26430.16
NUnit 3.7.1
NUnit3TestAdapter 3.8
MSTest 1.1.18


## Repro

Clone this repo

Build and you should see 2 tests in the test explorer

Select each of these, right click and select Profile Test

One should work, the MSTest one (TestItMsTest), the other (TestIt) might not work, which is the NUnit one.  It will not do the profile, and complain in the Test Output window that there is no data in the buffers. 

After running the profile on the NUnit test, does your test disappear from Test Explorer

Confirm your finding by message me the result on twitter  [@OsirisTerje](https://twitter.com/osiristerje)


