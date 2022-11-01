# XML PARSER
This is a pure SAGE X3 4GL XML parser.  
No external application or library is needed nor database stored procedures.  
What you need is:  
1. the ZMC01XMLRSAX file to be copied in your folder as is. It contains the core procedure to read and parse an XML file
2. create a source program to invoke the XMLPARSE Subprog of the ZMC01XMLRSAX. The source file YXMLTEST.src is an example
3. create a source program that handle the events raised by the ZMC01XMLRSAX parser. The source file YXMLHANDLER.src is an example
