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

## what is the company path 1
* what_is_the_company
  - action_what_is_the_company
  - utter_did_that_help
* affirm
  - utter_welcome

## what is the company path 2
* what_is_the_company
  - action_what_is_the_company
  - utter_did_that_help
* deny
  - utter_goodbye