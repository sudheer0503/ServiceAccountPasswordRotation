# ServiceAccountPasswordRotation
We use service accounts day to day in our production / engineering systems. Enterprize active directory would expect you to change the passoword every 'x' days. Using any vault and CD solution (I am using Azure KeyVault here), you can rotate it every day to reduce manual maintanance overhead. 

This is not limited a service account. You can also use this approch to rotate the password for any account. Imazine you have admin account for GitHub repo for which you want to change the password everyday, you can use this simple approach. 
