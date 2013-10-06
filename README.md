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
        /vizoal/services/playerlist/{rows}  
           
###Method			
	GET
				
###Header Parameters		
	1) Content-Type = application/json 

###Sample1 JSON Request (Insert a new bidderRegistration record)
```
{
    "status": {
        "code": "200",
        "message": "success",
        "errors": [],
        "debug": {
            "build": "1.0",
            "serverName": "ip-172-31-15-220",
            "duration": 6
        }
    },
    "result": [
        {
            "playerId": 2055,
            "firstName": "Joe",
            "lastName": "Mason",
            "fullName": "Joseph Mason",
            "nickName": "",
            "nationOfBirth": 122,
            "nationDisplay": 103,
            "nationOfBirthName": "Republic of Ireland",
            "cityOfBirth": "Plymouth",
            "dateOfBirth": "1991-05-13",
            "nationDisplay_fmid": 789,
            "age": 0,
            "weight": "73",
            "height": "178",
            "preferFoot": "right",
            "currentClub": 44,
            "currentClubName": "Cardiff City",
            "clubNumber": "20",
            "fmId": 28017168,
            "version": 3
        },
        {
            "playerId": 2066,
            "firstName": "Darcy",
            "lastName": "Blake",
            "fullName": "Darcy James Blake",
            "nickName": "",
            "nationOfBirth": 116,
            "nationDisplay": 116,
            "nationOfBirthName": "Wales",
            "cityOfBirth": "New Tredegar",
            "dateOfBirth": "1988-12-13",
            "nationDisplay_fmid": 801,
            "age": 0,
            "weight": "79",
            "height": "178",
            "preferFoot": "right",
            "currentClub": 46,
            "currentClubName": "Crystal Palace F.C.",
            "clubNumber": "",
            "fmId": 5131839,
            "version": 2
        }
    ]
}
```
