```
from dataclasses import dataclass


@dataclass(frozen=True)
class WhoIsSanchit:
    name: str = "Sanchit Balchandani"
    social_nick: str = "@inovizz"
    age: int = 33
    current_location: str = "Hyderabad, India "
    proficiency: str = "Python Programmer 🐍"
    total_exp: int = 10
    currently_working_on: str = "NodeJs, Gitlab-CI, Docker 🔭"
    currently_learning: str = "Async Programming, Go & preparing for CKAD 🌱"
    ask_me_about: str = "Python, Docker, HydPy & DSUG Hyd"
    summary: str = """Sanchit is a senior Python developer having 10 years of
                       IT experience. He has worked in multiple domains like 
                       - healthcare, ad-tech, infrastructure and automation. 
                       Majorly, he has been working in the backend side of the 
                       systems and also lately on SRE(DevOps). He is very 
                       passionate about Community Building, Python & 
                       Infrastructure. He strongly believes in the power of 
                       community and spends his free time contributing towards 
                       some open source communities like HydPy & DSUG Hyd."""


@dataclass(frozen=True)
class SkillSet:
    programming_languages: str = "Python, JavaScript, Go(Beginner), Solidity"
    operation_systems: str = "Linux, Windows"
    web_frameworks: str = "Django, Flask, Express, DRF, Channels"
    web_technolgies: str = "NodeJS, HTML, CSS, JQuery, ReactJS(Beginner)"
    dapp_development: str = "Blockchain, Truffle, Web3.js, Solidity, Geth, testRPC, Ethereum"
    devops: str = "Apache, Nginx, Docker, uWSGI, Gunicron, K8s(begineer), Jenkins, Bash"
    databases: str = "Postgres, MySQL, SQLite ,MongoDB"
    caching: str = "Redis, Memcache"
    version_control: str = "Git, Bitbucket, Gitlab"
    methodologies: str = "OOP, TDD, Agile, Scrum"
   

@dataclass(frozen=True)
class SocialProfiles:
    twitter: str = "https://twitter.com/inovizz"
    linkedin: str = "https://www.linkedin.com/in/inovizz"
    website: str = "https://inovizz.com/"
    stack_exchange: str = "https://ethereum.stackexchange.com/users/7790/sanchit"
 
```
