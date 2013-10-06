Vizoal API
==================================================

##APIs
<ol>
<li> Get popular players </li>
<li> Get players by club id</li>
<li> Get clubs by league id</li>
<li> Get player profile by player id </li>
<li> Get  </li>

</ol>

##1 : Get popular players
------------------------
###URL
        /   
           
###Method			
	POST
				
###Header Parameters		
	1) Content-Type = application/json 

###Sample1 JSON Request (Insert a new bidderRegistration record)
```
{
"auction_number":"T-1415",
"venue_id":"0,12413",

"buyer_info":{
    "company_name":"auction.com",
    "title":"",
    "first_name":"Waheed",
    "last_name":"A",
    "address":"address test",
    "city":"Irvine",
    "country":71,
    "state":12,
    "zip_code":"92604",
    "telephone":"111-111-1111",
    "cell":"111-111-1111",
    "email":"test@auction.com",
    "date_birth_verification":"true"
},

"buyer_additional_info":{
    "occupy_home_on_purchase":1,
    "purchase_price_range":"2",
    "how_you_hear":"howYouHear",
    "user_financing":false,
    "lender_name":"lenderNameTest",
    "lender_contact":"lenderContact",
    "spouse_or_cobuyer":2,
    "first_time_buyer":1,
    "investor":1,
    "pre_qualified":0,
    "employer":"auction.com",
    "job_title":"testing",
    "years_at_job":1,
    "gross_annual_income":1,
    "funds_available":false,
    "down_payment_at_purchase":2,
    "source_of_down_payment":1,
    "credit_history":1,
    "own_your_home":1,
    "co_signer":1,
    "second_home":1,
    "spouse_info":{
        "spouse_first_name":"cobuyer_first_name",
        "spouse_last_name":"cobuyer_last_name",
        "spouse_address":"cobuyer_address",
        "spouse_city":"cobuyer_city",
        "spouse_state":12,
        "spouse_country":71,
        "spouse_zip_code":"12345",
        "spouse_telephone":"111-111-1111",
        "spouse_cell":"111-111-1111",
        "spouse_email":"test@test.com"
    }
},

"buyer_broker":{
    "agent_first_name":"firstnameTest",
    "agent_last_name":"lastNameTest",
    "agent_email":"agentemailTest@email.com",
    "agent_phone":"111-111-1111",
    "agent_license":"agentLicenceTest",
    "license_state":"3"
},

"deposit_info":{
    "asset_ids":"1463007",
    "ip":"127.0.0.1",
    "payment_first_name":"firstname",
    "payment_last_name":"lastname",
    "payment_address":"1 manchly",
    "payment_city":"Irvine",
    "payment_state":5,
    "payment_country":71,
    "payment_zip_code":"92604",
    "card_number":"1818181818181818",
    "expiration_month":"03",
    "expiration_year":"2018",
    "cvv":"018",
    "deposit_amount":5,
    "credit_card_type":"1",
    "payment_type":"1",
    "bidder_name":"test"
},

"signed_info":{
    "sign_first_name":"Waheed",
    "sign_last_name":"A",
    "sign_date":"2013-06-28"
}

}
```
