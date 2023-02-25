# dProg 🔍
#### About
dProg is tool for Bug bounty program detection by similar <i>keyword</i> on bug bounty program page 
#### Picture
![image](https://user-images.githubusercontent.com/43540712/182825238-21d9f788-7b1c-4698-9287-8d5d729ac5d8.png)

#### Instalation
* <code>git clone https://github.com/xcapri/dProgBb.git</code>
* <code>cd dProgBb</code>
* <code>pip3 install -r helper/requirements.txt</code>
* and run like a below
#### Run
You can run like
* Oneliner with katana ``` cat list | httpx -silent | katana -silent | python3 dprog.py (--thread / -t) 20 | grep "POSSBOUNTY" | sort -u | notify -id dprog ```
* Oneliner <code>cat list | httpx | python3 dprog.py (--thread / -t) 20</code>
* Oneliner <code>cat list | ./hakrawler | sort -u | python3 dprog.py (--thread / -t) 10 | grep "POSSBOUNTY" | notify</code>
* Oneliner with notify <code>cat list | httpx | python3 dprog.py (--thread / -t) 20 | grep "POSSBOUNTY" | sort -u | notify -id dprog </code>
* By input list <code>py dprog.py</code>
#### Reference
* https://github.com/JoyGhoshs/findbb (FindBBProgram) 🤘
#### Demo
You can see this video for demo : <br>
https://youtu.be/z5IkjxTGHa8

### Contribution
If you want to contribute, you can add a path or regex around the bug bounty
* [Path](/helper/path.txt) 
* [Regex](/helper/regex.json)

### Support 
Follow my organization <br>https://github.com/tegal1337

### Thanks
