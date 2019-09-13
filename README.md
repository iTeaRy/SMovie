## Steps to Setup SMovie

1. **Clone the application**

	```bash
	git clone https://github.com/... .git
	cd SMovie
	```

2. **Install**
	+ Java "https://java.com/en/download/help/download_options.xml"
    + Maven "https://maven.apache.org/install.html"
    + npm "https://www.npmjs.com/get-npm"
    + PostgreSQL "https://www.enterprisedb.com/downloads/postgres-postgresql-downloads"
    
3. **Database**
    ```bash
	    create database smovie-dev
	```
    Set your `username` and `password` to application.properties file.

4. **Run the app**

    You can run the spring boot app by typing the following command -

	```bash
	mvn spring-boot:run
	```
	
	The server will start on port 8080. The spring boot app includes the front end build also, so you'll be able to access the complete application on `http://localhost:8080`.
    
    You can also package the application in the form of a `jar` file and then run it like so -
    	
	```bash
	mvn clean package
	java -jar target/smovie-0.0.1-SNAPSHOT.jar
	```