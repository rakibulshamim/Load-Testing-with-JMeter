# Load-Testing-with-JMeter

## Prerequisites:
1. Need to install jdk 1.8
2. Set JMeter home in environment variables


## How to run this file:
1. Clone jmx file to root(apache-jmeter-5.4.2\bin) folder
2. Run git bash or powershell or cmd in the folder
3. Then type following command to perform load test and generate report & log file:

```
jmeter -n -t Customers.jmx -l log.csv -e -o Reports
```

## Report View

![Screenshot 2021-12-25 141240](https://user-images.githubusercontent.com/36601919/147380699-04ed2aba-604b-49fc-86a7-96eb2bff464b.png)
![Screenshot 2021-12-25 141347](https://user-images.githubusercontent.com/36601919/147380705-67bbdff9-6a75-4a6b-a5aa-82d00915cd8c.png)
