# Bitespeed-Backend-Task

Identity Reconciliation 

Method: POST

Endpoint: `https://rohith-identity-reconciliation.onrender.com/identify`

Request Body:{
	"email": "accdsbcd@hillvalley.edu",
	"phoneNumber": "18245"
}

Response:	
{
    "contact": {
        "primaryContactId": 500,
        "emails": ["accdsbcd@hillvalley.edu"],
        "phoneNumbers": ["18245","182245"],
        "secondaryContactIds": [295]
    }
}

{
    "contact": {
        "primaryContactId": 10,
        "emails": ["accdsbcd@hillvalley.edu","fly@hillvalley.edu"],
        "phoneNumbers": ["18245","182245"],
        "secondaryContactIds": [500]
    }
}
#WebServer

![Screenshot (187)](https://github.com/Rohith2050/Identity-Reconciliation/assets/87187293/dfda8e24-6015-41fe-9fda-d938502f42c7)

#LocalHost
![Screenshot (186)](https://github.com/Rohith2050/Identity-Reconciliation/assets/87187293/81fadc2e-78a8-40cc-8442-e0439de54c9d)

