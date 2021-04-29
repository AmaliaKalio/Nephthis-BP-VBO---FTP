# Nephthis-BP-VBO---FTP
An (S)FTP VBO for BP built off of SSHNet and WinSCP. Currently expects the following DLL files in C:\bp to function: 
* Renci.SshNet.dll
* Renci.SshNet.xml
* WinSCP.exe
* WinSCPnet.dll

## FTP Put
Puts a file using unsecure FTP

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text

## SFTP Put
Puts a file using SFTP

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text

## SFTP Put with rsa 2048
Puts a file using SFTP with an rsa 2048 host key

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text
* hostkey - Text

## SFTP Get
Puts a file using SFTP

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text

## SFTP Get with rsa 2048
Puts a file using SFTP with an rsa 2048 host key

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text
* hostkey - Text

## SFTP Verify
Gets a list of files in a directory using SFTP

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text

### Outputs:
* Files - Collection

## SFTP Verify with rsa 2048
Gets a list of files in a directory using SFTP with an rsa 2048 host key

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text
* hostkey - Text

### Outputs:
* Files - Collection

## FTP Verify
Gets a list of files in a directory using unsecured FTP

### Inputs:
* FTPServer - Text
* FTPDir - Text
* FTPUsername - Text
* FTPPassword - Password
* sourceFile - Text
* targetFile - Text

### Outputs:
* Files - Collection
