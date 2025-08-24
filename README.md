# Should-Tero-Wear-A-Helmet-new

### Threat Modeling Very Shortly

<p>To summarize the and understand the article we first need to understand what is Threat modeling in general. Basically threat modeling means finding, assessing and addressing potential security threats to a system such as a website, an application or organization and dealing with them. Creatin a plan to keep risks limited and not let them create potential problems.</p>

###  1. Braiterman et al 2020: Threat modeling manifesto <br>
- Explaining why use threat modeling and who it should be for. <br>
- Explaining important values such as people and collaboration. <br>
- Introducing the 4 questions of threat modeling

## Question?
<p>How can we ensure that Threat modeling is a valid plan?</p>

### 2. Shostack 2022: "Worlds Shortest Threat Modeling Course" <br>
#### - The four questions of Thrat Modeling:
1. What are we working on?
2. What can go wrong?
3. What are we going to do about it?
4. Did we do a good enough job?

- Simple exercising such as system sketching, threat identification and planning mitigation.
- Explaining every aspect of threat modeling in short videos.

## Question?
<p>Would the four question framework be valuable for businesses?</p>

### 3. OWASP Threat Modeling Cheat Sheet (2021) <br>
#### - Threat modeling in 4 well thought steps:
1. Application lagging
2. Threat identification
3. Mitigation
4. Reviewing and further valuation
   
- Trying out Data Flow Diagrams for visualizing data.
- This article was based on adding visibility. Important things like understanding data flows for example.

## Question?
<p> For further projects would drawing simple data flow diagrams be enough for valuation?</p>

### 4. Darknet Diaries Podcast EP. 154: Hijacked Line:
- The podcasters had a hacker on the podcast named Connor Freeman and they talked to him about how they did everything why.
- Their main targtes were SMS-based 2FA codes for banks, crypto, wallets and emails.
- I liked the episode because it highlighted the need for better authentication methods.

## Question?
<p>If SMS based 2FA is still extremely vulnerable, why continue using them in places that hold a lot of personal information such as banks and big companies.</p>

# Security Hygiene

- Strong and unique passwords
- Enabling two step authentication
- Regualar software updates
- Be careful with emails and links
- Secure your WIFI network
- Try to limit personal information sharing
- Monitor accounts and devices
#### Source https://www.enisa.europa.eu/topics/cyber-hygiene

# Threat Model For Imaginary Company

## What are we working on?
<p>Our business is a online sport betting agency. We make it possible for people to invest their money to potentially get big winnings depending on the sport bets that they have placed. Obviously we will be trying to take care of the user accounts and payment details. Also betting odds algorithms are important to keep safe, because there can be people that would like to leak our odds and try to scam people. The website and the mobile app have to have a constant protection plus the payout systems because they are extremely easy to penetrate. The customer touchpoints would be the website, the application and customer chat or our email.</p>

## What can go wrong?
<p>Some STRIDE and CIA models that could be potential risks. Spoofing which means that hackers create fake betting accounts with stolen ID. Fraud which would be insiders leaking information to benefit themselves and others and to rig outcomes. Tampering could be manipulation of odds and match results. I think that the prioritized biggest risks would be frauds, dowtimes during big games and spoofers. I think that Match fixers and cybercriminals would probably be our biggest threats, because of their equal goals. Both want to manipulate odds for winning money and gain information. Also other apps and websites, our competitors. They would try to tarnish our image to gain customers.</p>

#### Source for Stride and Cia models: https://www.researchgate.net/figure/Mapping-STRIDE-with-CIA-3-security-attributes_tbl1_341515589

## What are we going to do about it?
<p>Simply just reinforce our protection systems. 
M Mitigate: Try to implement strong authentications such as face ID, Passports, Bank credentials and such
E Eliminate: Encrypting all payment data and deleting detail histories.
T Transfer: Invest in cyber insurances and fraud insurances. Make sure to gain trust by adding insurances.
A Accept: Sometimes there will be small problems and potentially the app or website will go down. These are all acceptable.
</p>

#### Source for understanding the META. https://standrewsconsulting.com/dealing-with-risk/avoid-mitigate-accept-transfer/

## Did we do a good enough job?
<p>Of course there could allways be stuff to further try and add but all in all plan sounds good. Just continue on reinforcing protection systems and monitoring them all the time. Updating the threat model is also a great way to stay in touch with everything and explain to all the team members of how everything works</p>
