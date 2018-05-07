## 1. Register an account in https://saucelabs.com

## 2. Copy Access Key of your account , Navigate Right side top -> Your name -> My Account

## 3. Open file `src/test/java/framework/CrudStudent.java` and change the URL of your server.

## 4. Run the following command.
```
# mvn clean install "-Dremote=true" "-DseleniumGridURL=http://<USERNAME-OF-ACCOUNT>:<ACCESS-KEY-YOUR-ACCOUNT>@ondemand.saucelabs.com:80/wd/hub"
``` 
