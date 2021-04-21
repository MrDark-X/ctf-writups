Not Common(easy)------------------------------->>>>>>>>>>>>>http://ictf.ninja/challenges#Not%20Common-7

![Screenshot from 2021-04-21 20-59-45](https://user-images.githubusercontent.com/70789856/115580838-1779c980-a2e5-11eb-8921-618941c40058.png)

HINT-It is important but yet people haven't made it a common practice.

when we open the website we can see only the robot image

![Screenshot from 2021-04-21 20-29-46](https://user-images.githubusercontent.com/70789856/115580927-2f514d80-a2e5-11eb-9be5-eca26a63cad6.png)

after i have gone through /robots.txt file but fond nothing.......

what would be the soluton???

1.install gobuster tool ---->>>> sudo apt-get install gobuster
2.use cmd----->>> gobuster dir -u https://incognito-web1.herokuapp.com/ -w /usr/share/wordlists/dirb/big.txt
3.![Screenshot from 2021-04-21 22-13-56](https://user-images.githubusercontent.com/70789856/115590742-f1f1bd80-a2ee-11eb-877d-5d6d5da5e020.png)
4.I found a bunch of 403's and a file named security.txt
5.when I open Security.txt i foung flag!!!!!!!!!!!!!!!!!!!!!!!!!!!
