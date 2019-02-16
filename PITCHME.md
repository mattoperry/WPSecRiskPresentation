
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

CBS / NBC / Meredith / NewsCorp / USAT / Postmedia / ESPN / Mother Jones / Think Progress / Grist / DFM ...

---

## enterprise

Capgemini / Credit Karma / Santander / Alaska Airlines / Nielsen ...

---

## technology

Facebook / Microsoft / Tinder / AirBnB ...

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

### fear of everything

### fear of nothing

---

@quote[One of the main cyber-risks is to think they don’t exist. The other is to try to treat all potential risks](Stéphane Nappo)

---

## risk management

---

@quote[the forecasting and evaluation of risks together with the identification of procedures to avoid or minimize their impact]

---

### risk management & WordPress

---

### 1 assess risks
### @css[ fragment ](2 build a response plan)

---

### not:

@css[ fragment ]( a technical deep-dive )

@css[ fragment ]( a list of tools )

@css[ fragment ]( tips/tricks/etc )

---

### assessing risks

---

## parade of horribles

---

### authentication

---

verifying identity

@css[ fragment ]( passwords / 2fa / sso / oAuth)

@css[ fragment ]( /wp-admin, /wp-json, frontend )

---

### over-permissioning

---

### old code

---

old = likely insecure

@css[ fragment ]( < 50% of WordPress installs are up to date )

@css[ fragment ]( for plugins, the situation is likely worse )

---

### bad code

---

core

@css[ fragment ]( plugins / themes )

---

### bad code is vulnerable code

---

SQL injection

@css[ fragment ]( XSS )

@css[ fragment ]( poor performance )

---

### evil fruit of bad code

@css[ fragment ]( data loss )

@css[ fragment ]( unauthorized access )

@css[ fragment ]( malware )

@css[ fragment ]( outage )

---

### hardware / networking issues

---

hosting

@css[ fragment ]( transparency & clear policies )

@css[ fragment ]( updated underlying stack -- PHP, nginx/apache ... )

@css[ fragment ]( certifications )

---

### external threats (robots)

---

(D)DOS / automated exploits / brute force / ...

@css[ fragment ]( Spam )

---

### human malfunction

---

people are often:  generous, good-natured, careful

@css[ fragment ]( people are sometimes:  greedy, evil, careless )

---

### flavors of human malfunction

---

leaving secret stuff laying around

@css[ fragment ]( sharing secrets unsafely )

@css[ fragment ]( fraud )

@css[ fragment ]( phishing )

---

## likelihood
## @css[ fragment ]( severity )

---

### likelihood

some events are orders of magnitude more likely than others

@css[ fragment ]( experience, advice, research, nature of client or project )

@css[ fragment ]( goal: determine rough relative likelihood )

---

### severity

what exactly happens when things go wrong?

@css[ fragment ]( what's the worst case scenario? )

@css[ fragment ]( sources:  experience, advice, research )

@css[ fragment ]( it's okay not to know! )

@css[ fragment ]( goal: determine rough relative severity )

---

### quantifying likelihood and severity

@css[ fragment ]( scales: binary? ternary? other scale? )

---

<img src="assets/images/scale.png">


---

### risk assessment matrix

---

<img src="assets/images/matrix1.png">

---

## example: a VIP client's WordPress risk matrix

---

possibly a sensitive or high-profile site
 
@css[ fragment ]( very active and well resourced code review/security/updates )

@css[ fragment ]( dedicated systems and security team and owned-to-metal hardware )

@css[ fragment ]( full control of our own data-centers and network ) 

---

<img src="assets/images/matrix2.png">

---

### actionability

to what extent can I myself control or respond to this kind of risk? 

---

<img src="assets/images/matrix3.png">

---

## severe & likely & actionable  

---

## tiers

1:  identity, human processes

@css[ fragment ]( 2:  code and updates ... actionable, variable severity, but well covered)

@css[ fragment ]( 3:  network/hardware, external threats ... even if severe, less likely and delegated)

---

## 2 taking action

---

### reducing severity and likelihood

@css[ fragment ]( severity: improved disaster recovery, backups, configuration changes, tighter user permissioning, redundancy )

@css[ fragment ]( likelihood:  better identity verification, improved human procedures, code scanning and review, security plugins )

---

###  make a disaster plan

exactly what to do if something goes wrong

@css[ fragment ]( who is responsible for different sorts of incidents? you? someone else? )

@css[ fragment ]( construct recipes for all likely scenarios including detailed procedures, commands to run, utilities and tools etc. )

@css[ fragment ]( plan to communicate during an incident )

---

<img src="assets/images/outage.png">

---

<img src="assets/images/disaster.png">

---

##  emergency toolkit

awareness:  threat matrix and responsibilities

@css[ fragment ]( policies: who is responsible for what, how to contact those people )

@css[ fragment ]( cleanup procedures for each likely scenario )

@css[ fragment ]( communication plan )

---

##  next steps

make your own threat matrix

@css[ fragment ]( write down your response procedures and make sure they can survive an outage )

@css[ fragment ]( who is responsible for what sort of incident? )

@css[ fragment ]( write down a full disaster plan )

@css[ fragment ]( consider communication -- to users, team, stakeholders )

---

# that's it!

@mattoperry | vip.wordpress.com