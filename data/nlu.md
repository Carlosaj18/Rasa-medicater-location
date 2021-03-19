## intent: greet
  examples: |
    - hey
    - hello
    - hi
    - hello there
    - good morning
    - good evening
    - moin
    - hey there
    - let's go
    - hey dude
    - goodmorning
    - goodevening
    - good afternoon

## intent: goodbye
  examples: |
    - good afternoon
    - cu
    - good by
    - cee you later
    - good night
    - bye
    - goodbye
    - have a nice day
    - see you around
    - bye bye
    - see you later
    - I am off
    - see you later alligator 
    - we will speak soon


"""" Requeriments to undetstand some inputs
identify the entitis []
labels the entities ()""""

## intent: inform
  examples: |
    - [Sitka] (location)
    - [Juneau] (location)
    - [Virginia] (location)
    - [Cusseta] (location)
    - [Chicago] (location)
    - [Tucson] (location)
    - [Columbus] (location)
    - [Valdez] (location)
    - [Preston] (location)
    - [Huntsville] (location)
    - [Boulder] (location)
    - [California] (location)
    - [Tulsa] (location)
    - [Colorado] (location)
    - [Goodyear] (location)
    - [Albuquerque] (location)
    - [Scottsdale] (location)
    - [Hibbing] (location)
    - [Norman] (location)
    - [San] (location)
    - [Peoria] (location)
    - [New] (location)
    - [Corpus] (location)
    - [Montgomery] (location)
    - [Wichita] (location)
    - [Aurora] (location)
    - [Denver] (location)
    - [Sierra] (location)
    - [Georgetown] (location)
    - [Birmingham] (location)
    - [Fayetteville] (location)
    - [Carson] (location)
    - [Raleigh] (location)
    - [Bakersfield] (location)
    - [Mobile] (location)
    - [Detroit] (location)
    - [Bunnel]l (location)
    - [Chattanooga] (location)
    - [Mesa] (location)
    - [Fernley] (location)
    - [Marana] (location)
    - [Yuma] (location)
    - [Little] (location)
    - [Athens] (location)
    - [Hartsville] (location)
    - [Port] (location)
    - [Tampa] (location)
    - [Fresno] (location)
    - [Unalaska] (location)
    - [Eloy] (location)
    - [Salt] (location)
    - [Jackson] (location)
    - [Fort] (location)
    - [Casa] (location)
    - [Charleston] (location)
    - [Henderson] (location)
    - [Durham] (location)
    - [Abilene] (location)
    - [Palmdale] (location)
    - [Babbitt] (location)
    - [Surprise] (location)
    - [Cape] (location)
    - [Shreveport] (location)
    - [Rio] (location)
    - [Savannah] (location)
    - [Reno] (location)
    - [Orlando] (location)
    - [North] (location)
    - [Tallahassee] (location)
    - [Amarillo] (location)
    - [St] (location)
    - [Knoxville] (location)
    - [Sacramento] (location)
    - [Clarksville] (location)
    - [Los Angeles] (location)
    - [New York] (location)
    - [Las Vegas] (location)
    - [San Diego] (location)
    - [San Antonio] (location)
    - [El Paso] (location)
    - [Kansas location] (location)
    - [San Francisco] (location)
    - [Santa Barbara] (location)
    - [home health agency] (facility_type)
    - [hospital] (facility_type)
    - [nursing home] (facility_type)
    - a [home health agency] (facility_type)
    - a [hospital] (facility_type)
    - a [nursing home] (facility_type)

## intent: search_provider
  examples: |
    - I need a [hospotal] (facility_type)
    - find me a nearby [hospotal] (facility_type)
    - show me [home health agencies] (facility_type)
    - [hospotal] (facility_type)
    - find me a nearby [hospotal] (facility_type) in [San Francisco] (location)
    - show me [home health agency] (facility_type)
    - [home health agency] (facility_type)
    - find me a nearby [healty agency] (facility_type) my zip code is [10119] (location)
    - find me a nearby [nursing home] (facility_type)
    - show me [nusing home] (facility_type)
    - [nusing home] (facility_type)
    - show me [nusing home] (facility_type)
    - find me a nearby [nursing home] (facility_type) my zip code is [10119] (location)
    - I need a [hospital] (facility_type) my zip code is [77494] (location)
    - my zip code is [30277] (location) and i need a [nursing home] (facility_type)
    - my zip code is [86602] (location) and i need a [hospital] (facility_type)
    - my zip code is [47516] (location) and i need a [home health agency] (facility_type)
    - i need a [nursing home] (facility_type) at [77474] (location)
    - i need a [hospital] (facility_type) at [77474] (location)
    - i need a [home health agency] (facility_type) at [77474] (location)
    - i am in [Amarillo] (location) and i need a [nursing home] (facility_type)
    - i am in [New York] (location) and i need a [hospital] (facility_type)
    - i am in [Las Vegas] (location) and i need a [home health agency] (facility_type)
    - i need a [nursing home] (facility_type) in [Katy] (location)
    - i need a [hospital] (facility_type) in [Waco] (location)
    - i need a [home health agency] (facility_type) in [Clarksville] (location)
    - show me [nursing home] (facility_type) in [Knoxville] (location)
    - show me [hospital] (facility_type) in [Durham] (location)
    - show me [home health agency] (facility_type) in [Reno] (location)
    - find me a nearby [home health agency] (facility_type) in [Reno] (location)
    - hi i am in [Tampa] (location) i need a [nursing home] (facility_type:b27b-2uc7)
    - hi i am in [San Diego] (location) i need a [nursing home] (facility_type:b27b-2uc7)
    - hi i am in [Nashville] (location) i need a [hospital] (facility_type:rbry-mqwu)
    - hi i am in [Sacramento] (location) i need a [home health agency] (facility_type:9wzi-peqs)
    - hi i am in [Springfield] (location) i need a [nursing home] (facility_type:b27b-2uc7)
    - hi i am in [Atlanta] (location) i need a [hospital] (facility_type:rbry-mqwu)
    - hi i am in [Chicago] (location) i need a [home health agency] (facility_type:9wzi-peqs)
    - hi i am in [Santa Cruz] (location) i need a [hospital] (facility_type:b27b-2uc7)
    - hi i am in [Boston] (location) i need a [home health agency] (facility_type:rbry-mqwu)
    - hi i am in [Tampa] (location) i need a [nursing home] (facility_type:b27b-2uc7) 
    - hello i am in [San Diego] (location) i need a [hospital] (facility_type:rbry-mqwu)
    - hello i am in [Nashville] (location) i need a [home health agency] (facility_type:9wzi-peqs)
    - hello i am in [Sacramento] (location) i need a [nursing home]
    - hello i am in [Springfield] (location) i need a [hospital] (facility_type:b27b-2uc7)
    - hello i am in [Atlanta] (location) i need a [home health agency] (facility_type:9wzi-peqs)
    - hello i am in [Chicago] (location) i need a [nursing home] (facility_type:b27b-2uc7)
    - hello i am in Santa Cruz i need a [hospital] (facility_type:b27b-2uc7)
    - hello i am in Boston i need a [home health agency] (facility_type:9wzi-peqs)
    - Good morning i am in Tampa i need a [nursing home] (facility_type:b27b-2uc7)
    - Good morning i am in San Diego i need a [hospital] (facility_type:b27b-2uc7)
    - Good morning i am in Nashville i need a [home health agency] (facility_type:9wzi-peqs)
    - Good morning i am in Sacramento i need a [nursing home] (facility_type:b27b-2uc7)
    - Good morning i am in Springfield i need a [hospital] (facility_type:b27b-2uc7)
    - Good morning i am in Atlanta i need a [home health agency] (facility_type:9wzi-peqs)
    - Good morning i am in Chicago i need a [nursing home] (facility_type:b27b-2uc7)
    - Good morning i am in Santa Cruz i need a [hospital] (facility_type:b27b-2uc7)
    - Good morning i am in Boston i need a [home health agency] (facility_type:9wzi-peqs)
    - Hello again i need a [nursing home] (facility_type:b27b-2uc7) in [Katy] (location)
    - Hello again i need a [hospital] (facility_type:b27b-2uc7) in [Waco] (location)
    - Hello again i need a [home health agency] (facility_type:9wzi-peqs) in [Clarksville] (location)
    - Good morning i need a [nursing home] (facility_type:b27b-2uc7) in [Katy] (location)
    - Good morning i need a [hospital] (facility_type:b27b-2uc7) in [Waco] (location)
    - Good morning i need a [home health agency] (facility_type:9wzi-peqs) in [Clarksville] (location)
    - Can you tell me a [nursing home] (facility_type:b27b-2uc7) in [Oklahoma City] (location)?

## intent: affirm
  examples: |
    - yes
    - y
    - indeed
    - of course
    - that sounds good
    - correct

## intent: deny
  examples: |
    - no
    - never
    - I don't think so
    - don't like that
    - no way
    - not really
    - not today
    - no thanks 
    - no thank you
    - uh no
    - noope
    - do you have something else
    - no this does not work for me

## intent: mood_great
  examples: |
    - perfect
    - great
    - amazing
    - feeling like a king
    - wonderful
    - I am feeling very good
    - I am great
    - I am amazing
    - I am going to save the world
    - super stoked
    - extremely good
    - so so perfect
    - so good
    - so perfect

## intent: mood_unhappy
  examples: |
    - my day was horrible
    - I am sad
    - I don't feel very well
    - I am disappointed
    - super sad
    - I'm so sad
    - sad
    - very sad
    - unhappy
    - not good
    - not very good
    - extremly sad
    - so saad
    - so sad

## intent:bot_challenge
  examples: |
    - are you a bot?
    - are you a human?
    - am I talking to a bot?
    - am I talking to a human?

## regex:location
  examples: |
    - [0-9]{5}

## synonym:xubh-q36u
  examples: |
    - hospital
    - hospitals 

## synonym:9wzi-peqs
  examples: |
    - home health agency
    - home health agencies  

## synonym:b27b-2uc7
  examples: |
    - nursong home
    - nursing homes