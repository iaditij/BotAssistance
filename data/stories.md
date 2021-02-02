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

## story: name
*  name
  - action_get_name
  -slot{"name": "Atul"}
  - utter_ask_name

## story: enter_phone_number
*  phone_number
   - action_get_number
   - slot{"phone_number": "9051328610"}
   - utter_ask_phone_number
   
## story: enter_email_address
*  email_address
   - action_get_email
   - slot{"email_address": "iamcdef@gmail.com"}
   - utter_ask_email_address

## story: book_appt
*  Book appointment
   - utter_bookappt
  

## story: affirm
*  affirm
   - utter_affirm

## story: cancel_appt
* Cancel appointment
  - utter_cancel_appt

