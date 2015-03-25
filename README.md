# wercker-box-nodejs-latex
This wercker box inherits wercker/ubuntu12.04-webessentials@1.0.4 and installs texlive-full on top of it.   
It's used for juwit-team organisation ci testing.   
- @1.0.1: Use node v0.12   
- @1.1.0: Change inheritance from wercker/ubuntu12.04-nodejs0.10 to wercker/ubuntu12.04-webessentials@1.0.4   
- @1.1.1: Generate ssh-key for github machine user with readonly access to juwit-team repositories. Do not use this key in any other way, it's not safe.    
[![wercker status](https://app.wercker.com/status/6cdc632d16eebec9b69fe86709d54d45/m "wercker status")](https://app.wercker.com/project/bykey/6cdc632d16eebec9b69fe86709d54d45)
