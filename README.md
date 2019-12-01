# MessageParser_5G
The decoding tool can decode 5G RRC protocol messages, including any version of the RRC protocol.


This tool identifies the RRC asn.1 structure through the asn1 configuration file.Before starting the software, you need to place the asn1 configuration file in the same directory as the executable.

The way to generate the tool for asn1 is as follows:

1.Save the RRC protocol to be decoded as TXT file;

2.Open the console and execute the following command:

  txt2asn1.exe 38331-f30.txt

which generate the asn1 configuration file 38331-f30.asn1

txt2asn1.exe is the conversion tool, which can be obtained on Dybinx/txt2asn1.
