# Microservices_V1
Microservices_V1

# URL

# limit-service
http://localhost:8080/limits
http://localhost:8080/fault-tolerance-example

# spring-cloud-config-server
http://localhost:8888/limits-service/qa
http://localhost:8888/limits-service/dev
http://localhost:8888/limits-service/default

# currency-exchange-service
http://localhost:8000/currency-exchange/from/AUD/to/INR
http://localhost:8001/currency-exchange/from/AUD/to/INR

# currency-conversion-service
http://localhost:8100/currency-converter/from/USD/to/INR/quantity/5998
http://localhost:8100/currency-converter-feign/from/AUD/to/INR/quantity/50

# netflix-zuul-api-gateway-server
http://localhost:8765/currency-exchange-service/currency-exchange/from/AUD/to/INR
http://localhost:8765/currency-conversion-service/currency-converter-feign/from/AUD/to/INR/quantity/50
