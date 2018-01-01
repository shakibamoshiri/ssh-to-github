  
█░░░█ █▀▀ █░░ █▀▀ █▀▀█ █▀▄▀█ █▀▀    
█▄█▄█ █▀▀ █░░ █░░ █░░█ █░▀░█ █▀▀    
░▀░▀░ ▀▀▀ ▀▀▀ ▀▀▀ ▀▀▀▀ ▀░░░▀ ▀▀▀   
to ssh-to-github with screen-shot  

## steps:  

### 01:   
 1. Go to your home directory of your machine.  
 2. Generate a new pair keys.  
 3. Copy it into your keyboard buffer.  
 4. Go to your github account.  

![ssh-to-github.1](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.1.png)   

---  

### 02:    
 5. Go to your github setting and find SSH section a click on: **New SSH Key**.   
 
![ssh-to-github.2](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.2.png)  

---  

### 03:    
 6. Add a title, any thing you like.  
 7. Paste here your Public Key (= id_rsa.pub).  
 
![ssh-to-github.3](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.3.png)

---

### 04:  
 8. You should see something like this, that shows it is not active.  
 9. Okay. Go back to your home directory.  
 
![ssh-to-github.4](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.4.png)

---  

### 05:    
 10. Try to test ssh: `ssh -T git@github.com`.   
 11. Type `yes` and press Enter. You should see your username.   
 12. Go back again to your github.   
 
![ssh-to-github.5](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.5.png)  

---  

### 06:    
 13. You should see that your key is active. Its color is now green.  
 
![ssh-to-github.6](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.6.png)  

---

### 07:    
 14. Okay. Create a new repository.    
 
![ssh-to-github.7](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.7.png)

---  

### 08:    
 15. Go to the newly created repository and click on: **clone or download**.    
 16. Copy ssh link and come back on your machine.  

![ssh-to-github.8](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.8.png)

---  

### 09:    
 17. Initialize a new repository and add your remote repository address.    

![ssh-to-github.9](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.9.png)  

---  

### 10:  
 18. Lastly try: `git push -u origin master`. It should **NOT** ask you for your password.  

![ssh-to-github.10](https://github.com/k-five/ssh-to-github/blob/master/shot/ssh-to-github.10.png)  


---

### NOTE:  
 - There are some **typo** on some screen-shots and I apologize for those.  
 - For troubleshot see [this link](https://help.github.com/articles/connecting-to-github-with-ssh/).  