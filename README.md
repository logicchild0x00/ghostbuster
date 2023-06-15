# ghostbuster
Any2Any document converter

The main goal of this project to create a library to convert any file format to any other file format.
It might use a common/base format, such as XPS file

Example:
XPS as a target format:
PS -> XPS
PCL -> XPS
PDF -> XPS

XPS as a source format:
XPS -> PS
XPS -> PCL
XPS -> PDF

XPS as a mediator:
PS -> PDF: will be executed as: PS -> XPS -> PDF
and so on...

So, the first thing is to build the models of XPS, or a graphics abstraction layer

-----------------------------
Happy to accept any ideas :)
