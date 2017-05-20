# Interlude Client/Server Chat program
Interlude acts like an IRC but with the difference that all the private messages are PGP encrypted.  
Not even the server ifself can read the message.

# Installation
Install the build tools to compile the program

## Ubuntu/Debian

```bash
sudo apt-get install gcc make
```

## openSUSE

```bash
zypper install gcc make
```

## macOS

```bash
brew install gcc make
```

# Compiling
On every platform, just use the command 
```bash
make
```
to build the software

# Usage

## Server
A Linux server is crucial for running the whole chat since it's server based.  
Simply start a server with
```bash
./server [port]
```
Please be aware that you need to open the port you specified.

## Client
As a client you need to connect to a server which handles the messages, etc..  
```bash
./client [ip-address] [port]
```
The specified port doesn't need to be open if you are a client.