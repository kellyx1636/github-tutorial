# GitHub Tutorial

_by Kelly Xiong Chen_

---
## Git vs. GitHub
|          Git               |            Both                     |               GitHub             |
|----------------------------|-------------------------------------|----------------------------------|
| Can be used offline        | Used for collaborative projects     | Where you push your commits      |
| Kind of private and public |    Can clone others' projects       | Can fork projects                |
| Where code can be changed  | User can looks at other users' work |  Find SSH or HTTP links          |
| Need a link to connect your repository (on GitHub) to your local repository |         |Where you can get a pull requests |
| Where workspaces are made  |                                     | Can only be used online          |    

---
## How to set up a GitHub account?
1) There are two ways of signing up and they are the following:
* Go to [**GitHub**](https://github.com/) and click "Sign Up".
* Go to [**Cloud9**](https://c9.io/) and click the octocat symbol.
    * [Wondering how an octocat look like? Click here!](https://www.google.com/imgres?imgurl=http%3A%2F%2Fimage.flaticon.com%2Ficons%2Fsvg%2F25%2F25231.svg&imgrefurl=http%3A%2F%2Fwww.flaticon.com%2Ffree-icon%2Fgithub-logo_25231&docid=DUAJHENWuAj-AM&tbnid=ZRPc5QkTPcqMLM%3A&w=438&h=438&bih=794&biw=1600&ved=0ahUKEwihwo341PXPAhWF2T4KHe23C3IQMwg_KAEwAQ&iact=mrc&uact=8)
    * I suggest you use this method because it connects your GitHub and Cloud9 accounts.

2) Fill in the information that is needed.
* This includes: creating a username, entering your email address, and securing your account with a strong password.
    * If you went to Cloud9 and signed up your GitHub account, go to the gear icon (in the top-right) and click "Connected Services" to make sure that your Cloud9 account is connected with your GitHub account. 

3) Verify your email by checking if GitHub sent you an email.

### SSH Keys
1) Make sure that you are signed into your GitHub account, but also have your Cloud9 account opened in another tab.

2) On the top-right side of the webpage, click on your avatar/icon/profile picture.

3) After, on the left side of the webpage, you will find a list called "Personal settings".

4) In that list, you will find "SSH and GPG keys". When you do, click on it.

5) Name your SSH key, "cloud9". Not your GPG.
* Since it is case sensitive, that means that "cloud9" should be in **ALL LOWER CASE**

6) Go to your Cloud 9 tab and click the gear icon that is on the top-right of the webpage.

7) In the left side of the webpage, find "SSH Keys" and click it.

8) Copy the long link that is in the darker-colored box. 
* It should have "ssh-rsa" in the beginning and your email in the end.

9) Go back to your GitHub tab and paste your link.

10) In the same tab, open "github-learning IDE".

11) Type "ssh -T git@github.com" and press ENTER. (Side note: The link that you see here should not lead you to another page.)

12) A message should pop up and confirm that you are "successfully authenticated".
---
## Repository Setup



---
## Workflow & Commands