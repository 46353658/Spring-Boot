"course-api" uses hardcoded data;

"course-api-data" uses an embedded database;

"course-api-data - Including courses without .jar" includes a courses table under topics, .jar deleted from the target folder, rename the root folder to "course-api-data", and run mvn clean install;
