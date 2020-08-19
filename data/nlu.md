## intent:affirm
- yes
- yep
- yeah
- indeed
- that's right
- ok
- great
- right, thank you
- correct
- great choice
- sounds really good
- thanks
- Yes
- Thanks

## intent:deny
- no
- nope
- not needed
- no, thank you
- nah
- No

## intent:goodbye
- bye
- goodbye
- good bye
- stop
- end
- farewell
- Bye bye
- have a good one
- Bye
- Thanks bye

## intent:greet
- hey
- howdy
- hey there
- hello
- hi
- good morning
- good evening
- dear sir
- Hi
- Hey

## intent:restaurant_search
- i'm looking for a place to eat
- I want to grab lunch
- I am searching for a dinner spot
- I am looking for some restaurants in [Delhi](location).
- I am looking for some restaurants in [Bangalore](location)
- show me [chinese](cuisine) restaurants
- show me [chines](cuisine:chinese) restaurants in the [New Delhi](location:Delhi)
- show me a [mexican](cuisine) place in the [centre](location)
- search for restaurants
- anywhere in the [west](location)
- I am looking for [asian fusion](cuisine) food
- I am looking a restaurant in [294328](location)
- in [Gurgaon](location)
- [South Indian](cuisine)
- [North Indian](cuisine)
- [Italian](cuisine)
- [Chinese](cuisine:chinese)
- [chinese](cuisine)
- [Lithuania](location)
- Oh, sorry, in [Italy](location)
- in [delhi](location)
- I am looking for some restaurants in [Mumbai](location)
- I am looking for [mexican indian fusion](cuisine)
- can you book a table in [rome](location) in a [moderate](price:mid) price range with [british](cuisine) food
- [central](location) [indian](cuisine) restaurant
- please help me to find restaurants in [pune](location)
- Please find me a restaurantin [bangalore](location)
- [mumbai](location)
- show me restaurants
- please find me [chinese](cuisine) restaurant in [delhi](location)
- can you find me a [chinese](cuisine) restaurant
- [delhi](location)
- please find me a restaurant in [ahmedabad](location)
- please show me a few [italian](cuisine) restaurants in [bangalore](location)
- can you find some [italian](cuisine) restaurants in [bangalore](location) and send an email at [venkatesh_datta@yahoo.com](email)
- my email is [sample@gmail.coim](email)
- find me a [North Indian] restaurant with [moderate](price:mid) price range in [Delhi](location)
- send me the results at [dummy@aol.org](email)
- I am looking for [low](price) priced restaurant in [Ahmedabad](location) that serves [Italian](cuisine) food
- I am looking for [moderate](price:mid) priced restaurant in [Ahmedabad](location) that serves [Italian](cuisine) food
- I am looking for [high](price) priced restaurant in [Ahmedabad](location) that serves [Italian](cuisine) food
- I am looking for a [fancy](price:high) restaurant in [Mumbai](location) that serves [South Indian](cuisine) food
- find me an [inexpensive](price:low) restautant in [Hyderabad](location)
- look for [South Indian](cuisine) restaurants [between 300 and 700](price:mid)
- [low](price)
- [mid](price)
- [< 300](price)
- [high](price)
- [dummy@xyz.com](email)
- find a restaurant
- Find a restaurant
- [Hyderabad](location)
- Mexican
- Find me a restaurant
- [Delhi](location)
- [venkatesh_datta@yahoo.com](email)
- Search for a [fancy](price:high) restaurant in [Ahmedabad](location)
- [venkateshdatta2601@gmail.com](email)
- I am looking for [inexpensive](price:low) restaurants in [Pune](location) that serves [North Indian](cuisine) cuisine
- [Mexican](cuisine)
- Find me a [mexican](cuisine) restaurant in [hyderabad](location)
- Find me a [mexican](cuisine) restaurant in [hyderabad](location)
- [high](price)

## synonym: Kolkata
- calcutta

## synonym:4
- four

## synonym:American
- Find me

## synonym:Delhi
- New Delhi
- Dilli

## synonym:bangalore
- Bengaluru
- Blr
- Bangaluru

## synonym:chennai
- madras

## synonym:chinese
- chines
- Chinese
- Chines

## synonym:high
- fancy
- hifi
- expensive

## synonym:hyderabad
- Hyd
- Hydrabad
- Hydarabad

## synonym:low
- inexpensive
- < 300
- less than 300
- cheaper
- cheap
- easy on pocket

## synonym:mid
- moderate
- between 300 and 700
- average

## synonym:mumbai
- bombay
- bombai

## synonym:pune
- puna

## synonym:vegetarian
- veggie
- vegg

## regex: email
- ^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$

## regex:greet
- hey[^\s]*

## regex:pincode
- [0-9]{6}

## lookup: price
- low
- high
- mid

## lookup: cuisine
- chinese
- italian
- mexican
- american
- north indian
- south indian
