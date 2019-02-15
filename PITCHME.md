
### WordPress security: a risk assessment approach

#### Matt Perry, WordPress VIP

---

# Hello!

### Matt Perry | Lead Engineer
### WordPress VIP
---

### What is VIP?

@css[ fragment ](WordPress in the enterprise)

@css[ fragment ](an Automattic company)

---

## who we work with

---

## media

CBS / NBC / Meredith / NewsCorp / USAT / Postmedia / ESPN / Mother Jones / Think Progress / Grist / DFM

---

## enterprise

CapGemini / CreditKarma / Santander / Alaska Airlines / Nielsen

---

## technology

Facebook / Microsoft / Tinder / AirBnB

---

## free clients to publish

---

## scaling | security
 
---

# security

---

passwords? authentication? 2fa?

@css[ fragment ](updates?)

@css[ fragment ](bad code?)

@css[ fragment ](hosting/hardware/networking etc?)

@css[ fragment ](defense against external threats?)

@css[ fragment ](human procedures?)

---

confusion

---

what this talk is:

- definitions: types of threats
- risk analysis: assess and define
- practical steps: build your emergency toolkit
- some tales from VIP

---

what this talk is not:
- a technical deep-dive into application security
- a survey of tools
- a list of tips and tricks

---

authenticaion:  verifying identity

---

passwords / sso / 2fa

(/wp-admin, wp-json)

---

2fa

---

updates:  old  = possibly insecure

[stat about the install base of older versions of WordPress before security releases]

---

autoupdates

---

plugins and security:

how active is the plugin?

how capable and responsive is the author?

---

mechanisms of evil

---

SQL injection

---

XSS

---

abuse vectors

---

learning to attack = learning to defend 

where to learn more

---

hosting / hardware / networking

---

what to look for

---

cetifications

recent versions of underlying software (PHP, nginx/apache etc.)

---

external threats:

DDOS / abusive crawling

---

dual responsibility: you / provider

proxy or wall between you and the world

network-level measures

___

how does this plugin actually work?

---

list of security plugins

---

humans

generous, good-natured, concientous

greedy, evil, sloppy

---

"human engineering"

(impersonation fraud)

---

leaving secret stuff laying around

---

authentication / updates / bad code / hosting & external attacks / humans

---

many things to worry about, limited amount of time to worry

---

risk analysis

---

defintion:  evaluation of risks to determine their severity (liklihood of a given event and consequences if it happens)

goal:  informed decision making, clear lines of responsibility

---

[a few more slides about risk assessment in general]

---

what is the level of risk?  high / uncertain / low

---

organizing risk

---

demo: risk matrix 

---

who is responsibile for mitigating the risk?

---

when a 3rd party is responsible:

- policies
- points of contact
- what if

---

when you are responsible:
- set your own policy
- dependency awareness (list of plugins / themes / tools)
- what if

---

what if
- plan for things to go wrong
- roles and actions scenarios
- emergency vs. routine communication
- keeping clients / stakeholders informed

---

disaster recovery

- identify/eliminate vulnerabilites
- restore from backup
- user access

---

data loss

backup policy

communication

---

emergency toolkit:

- awareness:  threat matrix and responsibilities
- policies: who is responsible for what
- procedures:  if x then y per scenario (disaster recovery)
- communication plan

---

example:  VIP

---

VIP threat matrix and responsibilities

---

VIP policies:  outage / response mode

---

VIP procedures example:  cleanup

---

communication plan:  example tweets / urgents

---

possible next steps:  
- use the threat matrix tool and start working on identifying responsibilities
- if/then worksheet
- publish your procedures
- communication plan

---

VIP is awesome // hiring