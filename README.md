```
from dataclasses import dataclass


@dataclass(frozen=True)
class WhoIsSanchit:
    name: str = "Sanchit Balchandani"
    proficiency: str = "Python Programmer 🐍"
    working_with: str = "EPAM Systems, India"
    passionate_about: str = "Community Building, Python, Docker & Free education"
    currently_working_on: str = "Python, NodeJs, Gitlab-CI, Docker"
    ask_me_about: str = "Python, Docker, HydPy & DSUG Hyd"


@dataclass(frozen=True)
class SkillSet:
    programming_languages: str = "Python, JavaScript, Go(Beginner), Solidity"
    operation_systems: str = "Linux, Windows"
    web_frameworks: str = "Django, Flask, Express, DRF, Channels"
    web_technolgies: str = "NodeJS, HTML, CSS, JQuery, ReactJS(Beginner)"
    dapp_development: str = "Blockchain, Truffle, Web3.js, Solidity, Geth, testRPC, Ethereum"
    devops: str = "Apache, Nginx, Docker, uWSGI, Gunicron, K8s(begineer), Jenkins, Bash"
    databases: str = "Postgres, MySQL, SQLite ,MongoDB"
    version_control: str = "Git, Bitbucket, Gitlab"
 

@dataclass(frozen=True)
class SocialProfiles:
    twitter: str = "https://twitter.com/inovizz"
    linkedin: str = "https://www.linkedin.com/in/inovizz"
    website: str = "https://inovizz.com/"
    stack_exchange: str = "https://ethereum.stackexchange.com/users/7790/sanchit"
 
```
