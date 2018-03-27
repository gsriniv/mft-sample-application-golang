How to use it ?
    a) install golanguage 
      https://golang.org/doc/install
    b) set the environment variable "GOPATH" till the application is downloaded. 
       eg.) _ set GOPATH=C:\Users\IBM_ADMIN\goWorkspace_
    c) build the application
         go build mftRESTsampleApplication.go 
         The above command will generate an executable by name mftRESTsampleApplication.exe
  
  All set to work with the sample application in go.

Options: 
The above executable will accepts hostName, portNumber and the serviceName (agent/transfer) as input arguments.

Example: 
1.) Execute the command with default value

   mftRESTSampleApplication.exe

2.) Execute the command by passing values

mftRESTsampleApplication.exe -host 9.23.34.45 -port 8989 -service transfer

3.) Execute the command by passing just required values

mftRESTsampleApplication.exe -service transfer
