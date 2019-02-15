**Hello!**

___

Matt Perry

WordPress Engineer

VIP

___

part of the Automattic family

WordPress in the enterprise

___

Excerpts from our client family:

Large media: CBS / NBC / Meredith (Time, People etc.) / NewsCorp / CNN / Gannett / Postmedia / ESPN

Enterprise: CapGemini / CreditKarma / Santander / Alaska Airlines / Nielsen

Technology:  Facebook / Microsoft / Tinder (!)

et al :  Mother Jones / Think Progress / Grist / DFM

___

scaling WordPress **securely**

___

what does **security** mean?

___

passwords? authentication? 2fa?

updates?

bad code?

hosting (hardware/networking etc?)

defense against external threats?

human procedures?

___



confusion

___



what this talk is:

- definitions: types of threats
- risk analysis: assess and define
- practical steps: build your emergency toolkit
- some tales from VIP

___


what this talk is not:
- a technical deep-dive into application security
- a survey of tools
- a list of tips and tricks

___


authenticaion:  verifying identity

___


passwords / sso / 2fa

(/wp-admin, wp-json)

___


2fa

___


updates:  old  = possibly insecure

[stat about the install base of older versions of WordPress before security releases]

___


autoupdates

___


plugins and security:

how active is the plugin?

how capable and responsive is the author?

___


mechanisms of evil

___


SQL injection

___


XSS

___


abuse vectors

___


learning to attack = learning to defend 

where to learn more

___


hosting / hardware / networking

___

what to look for

___

cetifications

recent versions of underlying software (PHP, nginx/apache etc.)

___

external threats:

DDOS / abusive crawling

___

dual responsibility: you / provider

proxy or wall between you and the world

network-level measures

___

how does this plugin actually work?

___


list of security plugins

___

humans

generous, good-natured, concientous

greedy, evil, sloppy

___

"human engineering"

(impersonation fraud)

___

leaving secret stuff laying around

___

authentication / updates / bad code / hosting & external attacks / humans

___


many things to worry about, limited amount of time to worry

___

risk analysis

___

defintion:  evaluation of risks to determine their severity (liklihood of a given event and consequences if it happens)

goal:  informed decision making, clear lines of responsibility

___

[a few more slides about risk assessment in general]
___

what is the level of risk?  high / uncertain / low

___

organizing risk

___

demo: risk matrix 

___

who is responsibile for mitigating the risk?

___

when a 3rd party is responsible:

- policies
- points of contact
- what if

___

when you are responsible:
- set your own policy
- dependency awareness (list of plugins / themes / tools)
- what if

___

what if
- plan for things to go wrong
- roles and actions scenarios
- emergency vs. routine communication
- keeping clients / stakeholders informed

___

disaster recovery

- identify/eliminate vulnerabilites
- restore from backup
- user access

___

data loss

backup policy

communication

___

emergency toolkit:

- awareness:  threat matrix and responsibilities
- policies: who is responsible for what
- procedures:  if x then y per scenario (disaster recovery)
- communication plan

___

example:  VIP

___

VIP threat matrix and responsibilities

___

VIP policies:  outage / response mode

___

VIP procedures example:  cleanup

___

communication plan:  example tweets / urgents

___

possible next steps:  
- use the threat matrix tool and start working on identifying responsibilities
- if/then worksheet
- publish your procedures
- communication plan

___

VIP is awesome // hiring