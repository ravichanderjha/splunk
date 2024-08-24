# splunk

docker run -d -p 8000:8000 -e "SPLUNK_START_ARGS=--accept-license" -e "SPLUNK_PASSWORD=Ravi@9910723164" --name splunk splunk/splunk:latest
