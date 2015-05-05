This repo is based on TCPDF v4.0.27 for PHP4 that is used in FrontAccounting v2.3.x
Several changes have been made to accommodate FA's function names and wrappings needed to use existing report classes.

TCPDF v4.1.003 is the last version of TCPDF to retain the class properties as normal var as in v4.0.0027. 
Thereafter, the class properties and methods become protected.
UTF8 to latin substitution is available in TCPDF v4.1.003 that can be backported into FA if needed in the unicode_data.php (unicode_data2.php in FA).
