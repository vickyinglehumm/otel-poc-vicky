docker run -d -p 8000:8000 -p 8088:8088 -e "SPLUNK_START_ARGS=--accept-license" --env-file .env  --name splunk splunk/splunk:latest
