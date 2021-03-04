# kong-konga-apigateway


for KONG install guide
https://docs.konghq.com/install/ubuntu/


for KONGA install guide
https://pantsel.github.io/konga/



For creatng the route:
curl i -X POST   --url http://localhost:8001/services/AccountBalanceInquiry/routes   --data 'name=AccountBalanceInquiry-route-v1'   --data 'paths[]=/AccountBalanceInquiry'
