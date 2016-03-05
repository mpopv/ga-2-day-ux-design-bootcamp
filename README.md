# General Assembly 2-day UX Design Bootcamp 

Project: WMATA pay / card-replacement app.

## Competitive Analysis

### Starbucks App Interface

Giftcard account management & payment app.

#### Pros

  * Auto-reload that triggers on set low balance
  * Rewards and incentives presented with delightful visuals
  * Multiple cards
  * Works anywhere
  * Broad focus
  * Must physically scan phone to pay

#### Cons

  * No credit to overdraft your account
  * Must load money onto 'cards'
  * Not easy to see total balance
  * No low balance notification

### EZ-Pass Device / Web Interface

Transit / auto toll automated payment device & web interface.

#### Pros

  * Credit to overdraft your account
  * Works multiple locations
  * Seamless payment

#### Cons

  * No good way of communicating problems
  * No rewards / incentives
  * Doesn't work beyond east coast
  * Must load money onto 'cards'

### Uber

#### Pros

  * Seamless payment; user does nothing
  * Credit to overdraft your account
  * Rating and reporting system for drivers and users

#### Cons

  * Main screen options overwhelming for new user; limited onboarding

### Ideas to improve upon

* Use a card-based system to allow backwards-compatibility with current card system; but also allow direct linking to bank account for those who don't want to worry about loading money onto cards.
* Provide some sort of take-ten-trips-get-one-free incentive for using app and linking bank account
* Make payment as seamless as possible: one tap or even RFID location-based proximity payment
* Very intuitive UI for sort-use users like tourists who don't have time/patience to learn a complicated, Uberesque UI
* Show balance on home screen so it's easy to see how much loaded

## Heuristic Evaluation

### Starbucks

#### User Control & Freedom

* Difficult to recover from accidental touch commands that bring user to a new screen.
* No post-hoc error correction.

#### Error Prevention

![error prevention](http://i.imgur.com/OoeqH0G.png)

* Popup with password lock before you can execute transactions.

#### Visibility of Systems / Status

![balance](http://i.imgur.com/8qtNFSo.jpg)

* Shows card(s) balance on main screen on Android version, but not iOS.
* On pay screen, pay button is activated and other top nav options grey out

#### Aesthetic and Minimalistic Design

* Flat ghost elements, monochrome hues, and uppercase geometric text guide users directly to simple set of actions.

## Persona Creation

### Proto-Persona Brainstorming

#### Urban Dweller

Takes Metro everywhere farther than waking distance, including work and on weekends.

#### Suburban Commuter

Lives outside DC and uses Metro primarily for commuting into the District for work on weekdays.

#### Occasional Suburban Visitor

Lives outside DC and drives to work, but occasionally takes Metro into the District for events.

#### Domestic Tourist

Visiting DC from elsewhere in the United States. Wants an easy solution, no time to learn a complex app.

#### International Tourist

Visiting DC from the rest of the world.

### Proto-Persona: Alex Cooper the Rosslyn Commuter

#### Sketch and Name

```
  _______________
 /                \
[ Hello! I'm Alex! ]
 \__   ___________/
     \/
```
![Alex the Commuter](http://i.imgur.com/2vxsj1o.jpg)

* Lives in Rosslyn in a downtown apartment
* 27 years old
* Uses an iPhone 6
* Pet parakeet
* Tech-savvy young working professional
* UX designer, so very judgemental about bad UX
* Works in downtown DC

#### Demographic Information

* Commutes every weekday during rush hours, walks to Rosslyn Metro
* Working professional

#### Pain Points

* Lines to pay at the kiosk
* No other option, limited ways
* Paying in advance online is a hassle and requires forethought
* Wait behind clueless tourists who can't use the paper slip readers, no quick option or fast lane
* Recent DC transplant
* No car; relies on train

#### Needs

* An iPhone-based system where accounts can be maintained and managed
* Robustness over ease of use: she's always on her phone and tech-savvy, so figuring out the UI not a problem

#### Potential Solutions

* Easy pay dashboard
* Another pay option--phone in addition to kiosk / online
* Automated withdrawal solutions
* Account setup once (passwords saved, card info)
* Rewards

### User Flow

* <> Visit home screen, see balance
* [] Balance is low: Press reload
* - [] (Optional) Select funding source
* - [] (Optional) Select amount to reload
* - [] Confirm
* [] Balance is good: Nothing
