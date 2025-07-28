## 🔧 Environment Variables

| Variable                          | Description                                                                                                      | Example                              |
|----------------------------------|------------------------------------------------------------------------------------------------------------------|--------------------------------------|
| ASPNETCORE_ENVIRONMENT           | Specifies the runtime environment (e.g., Development, Staging, Production). Determines which appsettings file to load, logging behavior, and feature toggles. | Production                           |
| EnvironmentSettings__Production  | Define URL to get image folder from s3 accordingly                                                               | https://s3.amazonaws.com/...         |
| AppSettings__RefreshTokenTTL     | Time-to-live (TTL) for the refresh token, usually measured in days.                                              | 7                                    |
| AppSettings__EmailFrom           | Default email address used in the "From" field when sending system emails.                                       | noreply@example.com                  |
| AppSettings__SmtpHost            | Hostname of the SMTP server used for sending emails.                                                             | smtp.gmail.com                       |
| AppSettings__SmtpPort            | Port number used for SMTP communication (typically 587 for TLS).                                                 | 587                                  |
| OriginsSetting__AllowedOrigins   | List of allowed domains for CORS (Cross-Origin Resource Sharing) access to the API.                              | https://example.com                  |
| AWSConfig__BucketName            | Name of the AWS S3 bucket used to store or retrieve resources. Access is granted via container IAM role.         | my-app-assets-bucket                 |
| AppSettings__LinkDownloadAppIOS  | Public App Store link to download the iOS version of the mobile app.                                             | https://apps.apple.com/...           |
| AppSettings__LinkDownloadAppAndroid | Google Play Store link to download the Android version of the mobile app.                                     | https://play.google.com/store/apps/... |
| AppSettings__SupportInformation  | Public support documentation URL for users (https://docs.magiqcloud.com/Engagement/).                            | https://docs.magiqcloud.com/Engagement/ |
| ENVIRONMENT_API_URL              | Base URL of the backend API for the current environment.                                                         | https://api.example.com              |
| MYSQL_HOST                       | IP address or hostname of the MySQL database server.                                                             ||
| MYSQL_PORT                       | Port used by the MySQL database server.                                                                          ||
| MYSQL_DATABASE                   | Name of the MySQL database to connect to.                                                                        ||
| FIREBASE_API_KEY                 | Firebase API key used by frontend applications to access Firebase services.                                      ||
| FIREBASE_AUTH_DOMAIN             | Firebase Auth domain used during authentication.                                                                 ||
| FIREBASE_PROJECT_ID              | Firebase project ID for the current environment.                                                                 ||
| FIREBASE_STORAGE_BUCKET          | Firebase Storage bucket name.                                                                                    ||
| FIREBASE_MESSAGING_SENDER_ID     | Firebase Cloud Messaging sender ID.                                                                              ||
| FIREBASE_APP_ID                  | Unique Firebase App ID used for identifying the project.                                                         ||
| FIREBASE_MEASUREMENT_ID          | Google Analytics Measurement ID for Firebase analytics tracking.                                                 ||
