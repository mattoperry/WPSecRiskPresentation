
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

@css[ fragment ](external/automated threats)

@css[ fragment ](human procedures?)

---

# confusion

_fear of everthing == fear of nothing_

---

## risk management

---

@quote[the forecasting and evaluation of risks together with the identification of procedures to avoid or minimize their impact]

---

### forecasting / evaluation
### @css[ fragment ](risk assesmnet)

---

@quote[One of the main cyber-risks is to think they don’t exist. The other is to try to treat all potential risks](Stéphane Nappo)

---

<span style="font-size:300pt;">RISK</span>

<span style="font-size:18pt;">risk</span>

---

### risk management & WordPress

---

### 1 understand WordPress risks
### @css[ fragment ](2 build a response plan)

---

### not covered

@css[ fragment ]( a technical deep-dive )

@css[ fragment ]( tools )

@css[ fragment ]( tips/tricks/etc )

---

### forecasting risks

---

## parade of horribles

---

### authenticaion

---

@css[ fragment ]( verifying identity )

@css[ fragment ]( passwords / 2fa / sso / oAuth)

@css[ fragment ]( /wp-admin, /wp-json )

---

### over-permissioning

---

### old code

---

updates:  old  = possibly insecure

[stat about the install base of older versions of WordPress before security releases]

---

### bad code

---

core

@css[ fragment ]( plugins / themes )

---

### flavors of bad code

---

SQL injection

@css[ fragment ]( XSS )

@css[ fragment ]( poor performance )

@css[ fragment ]( excessive surface area )

---

### learning more

@css[ fragment ]( learning to attack = learning to defend )

@css[ fragment ]( ONSWAP )

@css[ fragment ]( VIP )

---

### hosting/hardware/networking

---

cetifications/ask your host

@css[ fragment ]( updated underlying stack -- PHP, nginx/apache ... )

---

### external threats

---

DDOS (targeted, random)

@css[ fragment ]( proxies/firewalls/hosting providers )

---

### broken human proccesses

---

people are oten:  generous, good-natured, careful

@css[ fragment ]( people are sometimes:  greedy, evil, careless )

---

### flavors of broken processes

---

leaving secret stuff laying around

@css[ fragment ]( human engineering / unvalidated communication / phishing )

---

## forecasting risks
## @css[ fragment ]( evaluating risks )

---

organizing and characterizing risks

---

### impact

@css[ fragment ]( what exactly happens when things go wrong? )

@css[ fragment ]( what's the worst case scenario? )

@css[ fragment ]( sources:  experience, advice, research )

@css[ fragment ]( it's okay not to know! )

@css[ fragment ]( goal: determine rough relative severity )

---

### likelihood

@css[ fragment ]( some events are orders of magnitude more likely than others )

@css[ fragment ]( sources: experience, advice, research )

@css[ fragment ]( nature of the client and project )

@css[ fragment ]( goal: determine rough relative liklihood )

---

### picking a scale

@css[ fragment ]( binary? other numeric score? )

---

### risk assessment matrix

---

<img src="assets/images/matrix1.png">

---

## example: average VIP client

---

large number of diverse and sensitive clients
 
very active and well-resrouced review/security/updates

dedicated systems and security team

control of our own datacenters and network 

---

<img src="assets/images/matrix2.png">

---

<img src="assets/images/matrix3.png">

---

## actionability

---

<img src="assets/images/matrix3.png">

---

## severe, likely, actionable  

---

# tiers

1:  identity, human processes
@css[ fragment ]( 2:  code and updates ... actionable, variable severity, but well covered)

@css[ fragment ]( 3:  network/hardware, external threats ... even if severe, less likley and delegated)

---

## 2 building a response plan

---

### ownership

- set your own policy
- dependency awareness (list of plugins / themes / tools)

---

example: VIP

---

## mitigating risk

---

## plan for things to go wrong

---

what if
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