## happy_path
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "mumbai"}
    - slot{"cuisine": "italian"}
    - slot{"location": "mumbai"}
    - utter_get_price_range
* restaurant_search{"price":"low"}
    - slot{"price":"low"}
    - utter_should_email
* affirm
    - utter_get_email
* restaurant_search{"email":"sample@domain.org"}
    - slot{"email":"sample@domain.org"}
    - action_search_restaurants
    - utter_goodbye


## interactive_story_20200426
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - utter_get_price_range
* restaurant_search{"price":"high"}
    - slot{"price":"high"}
    - utter_should_email
* affirm
    - utter_get_email
* restaurant_search{"email":"dummy@xyz.com"}
    - slot{"email":"dummy@xyz.com"}
    - action_search_restaurants
* affirm
    - utter_goodbye

## interactive_story_6
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Delhi"}
    - slot{"location": "Delhi"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_get_price_range
* restaurant_search{"price": "low"}
    - slot{"price": "low"}
    - utter_should_email
* affirm
    - utter_get_email
* restaurant_search{"email": "venkatesh_datta@yahoo.com"}
    - slot{"email": "venkatesh_datta@yahoo.com"}
    - action_search_restaurants
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_location
* restaurant_search{"location": "Hyderabad"}
    - slot{"location": "Hyderabad"}
    - utter_get_price_range
* restaurant_search{"price": "mid"}
    - slot{"price": "mid"}
    - utter_should_email
* deny
    - action_search_restaurants
* affirm
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"price": "high", "location": "Ahmedabad"}
    - slot{"location": "Ahmedabad"}
    - slot{"price": "high"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "South Indian"}
    - slot{"cuisine": "South Indian"}
    - utter_should_email
* affirm
    - utter_get_email
* restaurant_search{"email": "venkateshdatta2601@gmail.com"}
    - slot{"email": "venkateshdatta2601@gmail.com"}
    - action_search_restaurants
* goodbye
    - utter_goodbye

## interactive_story_1
* restaurant_search{"price": "low", "location": "Pune", "cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - slot{"location": "Pune"}
    - slot{"price": "low"}
    - utter_get_price_range
* restaurant_search{"price": "high"}
    - slot{"price": "high"}
    - utter_should_email
* affirm
    - utter_get_email
* restaurant_search{"email": "venkatesh_datta@yahoo.com"}
    - slot{"email": "venkatesh_datta@yahoo.com"}
    - action_search_restaurants
* goodbye
    - utter_goodbye

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "mexican", "location": "hyderabad"}
    - slot{"cuisine": "mexican"}
    - slot{"location": "hyderabad"}
    - utter_get_price_range
* restaurant_search{"price": "high"}
    - slot{"price": "high"}
    - utter_should_email
* deny
    - action_search_restaurants
    - utter_goodbye
