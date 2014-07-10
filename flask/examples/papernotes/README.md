## PaperNotes

- What is PaperNotes?
	- A SQLite and Flask powered social network for paper readers. It is also a review website for papers.

- How do I use it?
    - 1. edit the configuration in the papernotes.py file or
       export an PAPERNOTES_SETTINGS environment variable
       pointing to a configuration file.
    - 2. fire up a shell and run this:
	```
	flask --app=papernotes initdb
	```
    - 3. now you can run minitwit:
	```
	flask --app=papernotes run
	```
	or 
	```
	flask --app=papernotes run --host=yourIPv4addr
	```
       the application will greet you on
       http://localhost:5000/ or http://ipaddress:5000
       
	
- Is it tested?
	- Run the `papernotes_tests.py` file to see the tests pass.
