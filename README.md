# download 2 binary files 
# dashboard and counting
# do unzip
# unzip counting-service_linux_amd64.zip
# unzip dashboard-service_linux_amd64.zip
# delete 2 zip files 
# rm counting-service_linux_amd64.zip dashboard-service_linux_amd64.zip
# to check network card
# ifconfig
# ./dashboard-service
# chmod +x dashboard-service
# chmod +x counting-service
# PORT=9002 ./dashboard-service
# browser 127.0.0.1:9002
# browser 192.168.8.107:9002
# PORT=8888 ./dashboard-service
# after run counting and back run dashboard
# PORT=8888 COUNTING_SERVICE_URL="http://localhost:9000" ./dashboard-service
# browser 127.0.0.1:8888
# localhost:8888
# user - browser - application
# perspective of browser - dashboard upstream
# perspective of dashboard app - broser downstream
# upstream down so counting service is unreachable
# end to end - user - browser - dashboard - counting
# new terminal 
# watch
# watch "lsof -i -P | grep dashboard"

#### counting ####
# new terminal
# PORT=9000 ./counting-service


# watch terminal
# watch "lsof -i -P | grep counting"
# browser
# localhost:9000
