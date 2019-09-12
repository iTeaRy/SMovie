## Steps to Setup SMovie

1. **Clone the application**

	```bash
	git clone https://github.com/... .git
	cd SMovie
	```

2. **Install**
	+ java "https://java.com/en/download/help/download_options.xml"
    + maven "https://maven.apache.org/install.html"
    + npm "https://www.npmjs.com/get-npm"

3. **Run the app**

    You can run the spring boot app by typing the following command -

	```bash
	mvn spring-boot:run
	```
	
	The server will start on port 8081. The spring boot app includes the front end build also, so you'll be able to access the complete application on `http://localhost:8081`.
    
    You can also package the application in the form of a `jar` file and then run it like so -
    	
	```bash
	mvn clean package
	java -jar target/smovie-0.0.1-SNAPSHOT.jar
	```