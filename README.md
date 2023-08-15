# Prometheus task 1

1- What are the different HTTP status code and explain meaning of each of them?

    Informational: Server has received the request and is continuing to process it
    Successful: Request was successfully received, understood and accepted
    Redirection: Client must take additional action to complete the request
    Client Error: Request contains bad syntax or cannot be fulfilled

2- What database is used by Prometheus?

    TSDB (Time Series DataBase)

3- What is the differnece between different metrics types ( counter , gauge , histogram)?

    Counter: is a metric that represents a monotonically increasing value, used to track things like the number of requests received or the total number of errors that have occurred
    Gauge: is a metric that represents a value that can go up or down over time, used to track things like the amount of memory used or the number of active connections to a system
    Histogram: is a metric that represents the distribution of a set of values over time, used to track things like request latencies or response sizes

4- Install prometheus on your localhost or on server in any cloud provider:
    
  ![Screenshot from 2023-08-15 15-29-44](https://github.com/maelghamrawy/Prometheus/assets/28117071/fdaa8042-9795-4273-b9c5-11570b1efa73)

  Add any new target to prometheus.yaml file and apply any query on it using promql language:
  ![Screenshot from 2023-08-15 15-31-18](https://github.com/maelghamrawy/Prometheus/assets/28117071/555675c5-a49b-4374-916d-b6c653544e78)
  ![Screenshot from 2023-08-15 15-32-44](https://github.com/maelghamrawy/Prometheus/assets/28117071/d902a308-4bdd-4c5d-a500-80c356c97c4d)

Using Some query:
  ![Screenshot from 2023-08-15 15-33-49](https://github.com/maelghamrawy/Prometheus/assets/28117071/c1e9733f-6728-4b1e-8832-b34df065f24d)
