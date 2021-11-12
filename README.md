# kotechnologies-jmeter
A Docker JMeter Setup
docker build -t jmeter:latest .

docker run -v C:\Users\vjk10\Documents\RSPB\jemeter:/opt/run -w /opt/run/output  -v C:\Users\vjk10\Documents\RSPB\jemeter\output:/opt/run/output justb4/jmeter:latest   -n -t /opt/run/google.jmx -o /opt/run/output/result -l /opt/run/output/result/result.jtl -f -e
