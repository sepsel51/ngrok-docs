
#### Example Request
```bash
curl \
-XPUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"terminate_at":"edge","min_version":"1.2"}' \
https://api.ngrok.com/endpoint_configurations/ec_2GjEzJ2fskcBbTAjCRt6hDxAONG/tls_termination
