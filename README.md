run:-
 `docker-compose up --build`
 
 to run the app

run this query:-

{
	allBooks {
		isn
		title
	}
}

and you should get this

{
    "errors": [],
    "data": {
        "allBooks": [
            {
                "isn": "123",
                "title": "Book of Clouds"
            },
            {
                "isn": "124",
                "title": "Cloud Arch & Engineering"
            },
            {
                "isn": "125",
                "title": "Java 9 Programming"
            }
        ]
    },
    "extensions": null
}