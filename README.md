# spring-webhook-sql-solver

Spring Boot app that:
- Sends a POST to the generateWebhook endpoint on startup,
- Receives a webhook URL and accessToken,
- Submits the final SQL query (solution) to the returned webhook using the provided accessToken.

## Build & Run
1. Ensure Java 17 and Maven installed.
2. Build:
   ```bash
   mvn clean package
   ```
   The runnable JAR will be in `target/`.

3. Run:
   ```bash
   java -jar target/spring-webhook-sql-solver-1.0.0.jar
   ```
