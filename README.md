![11](https://github.com/fpaezf/FastDL-Server/assets/28062918/b1762b7a-4544-4cf9-8f03-ed1c29c27f75)

# Simple FastDL Server
A simple fastDL file server that allows your game server clients to download custom content like maps, textures, models and sounds via HTTP.

Built in pure Visual Basic .NET, without third party libraries.


# Server setup
Setup this fastDL file server is quite easy and can be done in a few seconds. You just need an IP address, a port to listen for incoming requests and a root folder were to store the files you want to share.

### IP Address
If you're running FastDL server in a dedicated server, please input the server public IP address.

If you're running FastDL Server in a local computer, please input your local IP address and do router port forwarding to make it available from outside your network.

### Port
The port were FastDL server will listen for incoming client requests. Tipically all http servers will listen on port 80.

### Root folder
This is the main folder were you will store the files. By default is **"Application.StartupPath\Root\"**.

### Use all IPs
If checked, the server will listen for incoming connections in all network interfaces.

### Auto start server
If checked, the server will autostart at application launch.

### Test server
This button will open a new instance of the system default web browser and will try to navigate to the configured server address:port. if you can view the FastDl server welcome page, the server is correctly setup.

![aas](https://github.com/fpaezf/FastDL-Server/assets/28062918/67e93fff-c28e-4cea-ac8c-02e301c57711)
