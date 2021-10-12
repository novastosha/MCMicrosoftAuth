# MCMicrosoftAuth

**Result**: https://gyazo.com/29869b4e1438e89da8309b1843b3a118

> A quick snippet to log in with Microsoft Accounts

# Credits
  - [Microsoft Authentication Scheme](https://wiki.vg/Microsoft_Authentication_Scheme)
  - [MSMC / Hanro50](https://github.com/Hanro50) For allowing me to use his code to understand parts of the authentication
  - [frosty](https://github.com/egirlfrosty) For bullying me into using JsonObjects instead of class specific objects
  
This is a pretty simple snippet which allows you to connect to your Minecraft account through Microsoft's login window
(yes the code is kinda messy and I don't know if i have the will power to change it right now)
  
How to use it
- Just drag and drop the folder to your desired location (Of course because some people might ask this, yes in your MCP project @_@)
- To login just do:

```java
MicrosoftAuthentication.getInstance().loginWithPopUpWindow();
```

How to customize it
- In MicrosoftLoginWindow.java, you can change the CLIENT_ID (which is basically the background of the login page (you'll need an Azure application to do this))
- In that same class, you can also change the title, icon, window size etc which can be found in the class' constructor
