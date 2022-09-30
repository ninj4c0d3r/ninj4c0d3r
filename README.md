<img align="left" src="https://orhun.dev/img/crow.png">
<h3>Hey, Im Jonatas!</h3>
<p><em>Security Research at <a href="https://www.telefonica.com/">Vivo (Telefônica Brasil)
</a>
</em></p>
<p><b>OSCP | eJPT | DCPT</b></p>

---
<img align='right' src="https://media0.giphy.com/media/4eGUxJc4lplh6/200w.gif?cid=82a1493blwhxsqq6ehdvua4uy60937hjlhbbae4yzkexiqmc&rid=200w.gif&ct=g" width="230">


[![Twitter Follow](https://img.shields.io/twitter/follow/Exploitati0n?label=Follow)](https://twitter.com/intent/follow?screen_name=Exploitati0n)
[![Linkedin: Linkedin](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jonatasfil/)](https://www.linkedin.com/in/jonatasfil/)
![GitHub followers](https://img.shields.io/github/followers/ninj4c0d3r?label=Follow&style=social)

### 🎖️ Reports

- [CVE-2017-14135](https://www.cvedetails.com/cve/CVE-2017-14135/) - **Command Injection | Open DreamBox**
- [CVE-2022-1810](https://huntr.dev/bounties/9b2d7579-032e-42da-b736-4b10a868eacb/) - **Improper Access Control | Publify**
- [CVE-2022-1811](https://huntr.dev/bounties/4d97f665-c9f1-4c38-b774-692255a7c44c/) - **Bypass Restriction and File Upload Leads to XSS Stored | Publify**
- [CVE-2022-2062](https://huntr.dev/bounties/35593b4c-f127-4699-8ad3-f0b2203a8ef6/) - **SSRF Via SMTP Plugin | NocoDB**
- [CVE-2022-2063](https://huntr.dev/bounties/156f405b-21d6-4384-9bff-17ebfe484e20/) - **Account Takeover via Webhook Handlebars + API Reset Password | NocoDB**

-------

### 🔎 About me

```python
#!/usr/bin/env python

from base64 import b64decode
import pickle

def AboutMe():
    serialized = "gASVNQAAAAAAAAB9lCiMBE5hbWWUjAtKb25hdGFzIEZpbJSMA0FnZZRLFYwHQ291bnRyeZSMBkJyYXppbJR1Lg=="
    my_data = pickle.loads(b64decode(serialized))
    print(my_data)
    
if __name__ == ("__main__"):
    AboutMe()
```
