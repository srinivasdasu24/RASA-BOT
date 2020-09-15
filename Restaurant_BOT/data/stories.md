## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## interactive_story_1
* affirm
    - utter_happy
* goodbye
    - utter_goodbye
* goodbye
    - utter_goodbye

## greet_get_location
* greet
  - action_welcome_greet
* mood_great
  - utter_ask_location
* getting_location
  - action_set_location
  - slot{"location":"Visakhapatnam"}
* goodbye
