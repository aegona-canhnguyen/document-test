# document-test

## 🔧 Environment Variables

| Variable Name                     | Description                                                                                  | Example or Note                     |
|----------------------------------|----------------------------------------------------------------------------------------------|-------------------------------------|
| `ASPNETCORE_ENVIRONMENT`         | Specifies the runtime environment (`Development`, `Staging`, `Production`)                  | Affects logging, config loading     |
| `EnvironmentSettings__Production`| URL to access image folder from S3 for Production                                            | e.g., `https://s3.../images`        |
| `AppSettings__RefreshTokenTTL`   | TTL (in days) for refresh tokens                                                             | e.g., `7`                           |
| `AppSettings__EmailFrom`         | Default "From" address for system emails                                                     | e.g., `noreply@example.com`         |
| `AppSettings__SmtpHost`          | SMTP server hostname                                                                         | e.g., `smtp.sendgrid.net`           |
| `AppSettings__SmtpPort`          | SMTP port (commonly `587` for TLS)                                                           | e.g., `587`                         |
| `OriginsSetting__AllowedOrigins` | List of allowed origins for CORS requests                                                    | e.g., `https://example.com`         |
| `AWSConfig__BucketName`          | Name of the AWS S3 bucket used for storage access                                            | IAM Role-based access               |
| `AppSettings__LinkDownloadAppIOS`| iOS App Store download link                                                                  | Public link                         |
| `AppSettings__LinkDownloadAppAndroid` | Google Play Store download link                                                        | Public link                         |
| `AppSettings__SupportInformation`| URL to support documentation                                                                 | e.g., `https://docs.magiqcloud...`  |
| `ENVIRONMENT_API_URL`            | Base URL for the backend API                                                                 | e.g., `https://api.example.com`     |
| `MYSQL_HOST`                     | Hostname or IP of the MySQL server                                                           | e.g., `127.0.0.1`                   |
| `MYSQL_PORT`                     | MySQL server port                                                                            | e.g., `3306`                        |
| `MYSQL_DATABASE`                 | Name of the target MySQL database                                                            | e.g., `engagement`                  |
| `FIREBASE_API_KEY`               | Firebase API key for frontend                                                               | Store securely                      |
| `FIREBASE_AUTH_DOMAIN`           | Firebase Auth domain                                                                         |                                     |
| `FIREBASE_PROJECT_ID`            | Firebase project ID                                                                          |                                     |
| `FIREBASE_STORAGE_BUCKET`        | Firebase Storage bucket name                                                                 |                                     |
| `FIREBASE_MESSAGING_SENDER_ID`   | Firebase Messaging sender ID                                                                 |                                     |
| `FIREBASE_APP_ID`                | Firebase App ID                                                                              |                                     |
| `FIREBASE_MEASUREMENT_ID`        | Firebase Analytics Measurement ID                                                            |                                     |
