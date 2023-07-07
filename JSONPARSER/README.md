# JSON PARSER
This is a pure SAGE X3 4GL JSON parser.  
No external application or library is needed nor database stored procedures.  
What you need is:  
1. the ZMC02JSON file to be copied in your folder as is. It contains the core procedure to read and parse an XML file
2. create a source program to invoke the PARSE_JSON Subprog of the ZMC02JSON. The YJSONTEST.src is an example
3. create a source program that handle the events raised by the ZMC02JSON parser. The YJSONHANDLER.src is an example
