# An asp.net core 2.0 web api boilerplate using identity server 4
## SalesApi structure:
![](https://images2018.cnblogs.com/blog/986268/201803/986268-20180318201304285-2050116601.png)
You need to setup these environment variables:   
* **MLH:AuthorizationServer:ServerBase**, this is the authorization server base. such as http://localhost:5000.   
* **MLH:AuthorizationServer:SigningCredentialCertificatePath**, this is the authorization server certificate path. such as "E:/xxx.pfx".  
* **MLH:AuthorizationServer:SigningCredentialCertificatePassword**, this is the authorization server certificate password. such as "12345678"  
* **MLH:SalesApi:ServerBase**, this is the sales api server base. such as http://localhost:5100.     
* **MLH:SalesApi:ClientBase**, this is the sales client uri base. such as http://localhost:4200.  
