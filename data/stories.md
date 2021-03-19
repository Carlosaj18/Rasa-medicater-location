## happy_path 
* greet 
  - find_facility_types
* inform{"facility_type": "rbry-mqwu"}
  - facility_form 
  - form{"name": "facility_form"}
  - form{"name": null}
* inform{"facility_id": 4245}
  - find_healtcare_address
  - utter_address
* thanyou 
  - utter_goodbye

## happy_path2 
* search_provider{"location": "Austin", "facility_type": "rbry-mqwu"}
  - facility_form 
  - form{"name": "facility_form"}
  - form{"name": null}
* inform{"facility_id": "450871"}
  - find_healtcare_address
  - utter_address
* thankyou
  - utter_noworries

## happy_path_multi_requests 
* greet 
  - find_facility_types
* inform{"facility_type": "rbry-mqwu"}
  - facility_form 
  - form{"name": "facility_form"}
  - form{"name": null}
* inform{"facility_id": 4245}
  - find_healtcare_address
  - utter_address
 * search_provider{"facility_type": "rbry-mqwu"}
  - facility_form 
  - form{"name": "facility_form"}
  - form{"name": null}
* inform{"facility_id": 4245}
  - find_healtcare_address
  - utter_address

## hospital search happy path 
* greet 
  - utter_how_can_i_help
* search_provider{"facility_type":"hospotal", "location": "San Franciso"}
   - action_facility_search
   - slot{"address": "300 Hyde St, San Francisco"}
* thanks 
  - utter_goodbye

## hospital search + location 
* greet 
  - utter_how_can_i_help
* search_provider{"facility_type":"hospotal"}
   - utter_ask_location 
* inform{"location": "San Francisco"}
   - action_facility_search
   - slot{"address": "300 Hyde St, San Francisco"}
* thanks 
  - utter_goodbye

## story: happy path
  steps:
  - intent: greet
  - action: utter_greet
  - intent: mood_great
  - action: utter_happy

## story: sad path 1
  steps:
  - intent: greet
  - action: utter_greet
  - intent: mood_unhappy
  - action: utter_cheer_up
  - action: utter_did_that_help
  - intent: affirm
  - action: utter_happy

## story: sad path 2
  steps:
  - intent: greet
  - action: utter_greet
  - intent: mood_unhappy
  - action: utter_cheer_up
  - action: utter_did_that_help
  - intent: deny
  - action: utter_goodbye
