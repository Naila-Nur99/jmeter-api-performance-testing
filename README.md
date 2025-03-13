# JMeter API Testing & Performance Evaluation
## Description
This repository includes JMeter test plans for two API scenarios. The Booking API (booking.jmx) is designed for performance testing, including load and stress tests, to evaluate system stability. The Dmoney API (dmoney.jmx) focuses on functional testing of financial transactions, ensuring seamless deposits, money transfers, and payments.
## Technology I used
 - Apache JMeter
 - Postman
## Prerequisites
 - Apache JMeter installed
 - Java (JDK 17) installed
## How to run this project
- ### Clone the Repository
     - ```git clone https://github.com/Naila-Nur99/jmeter-api-performance-testing.git ```
     - ```cd jmeter-api-performance-testing ```
 
- ### Running the Booking API Test (Performance Test)
   - #### Steps
      - Open booking.jmx in JMeter.
      - Run the test for 5 minutes, then 10 minutes, then 20 minutes.
      - Check the HTML report for results.
      - If the load test passes, gradually increase the users to find the bottleneck (stress test).
      - Generate an HTML report and save results in booking-api-test-report.xlsx.
        
- ### Running the Dmoney API Test (Functional Test)
   - #### Steps
      - Open dmoney.jmx in JMeter.
      - Ensure the deposit.csv, sendMoney.csv, and payment.csv files are present.
      - Run the test to validate financial transactions.
## Results & Reports
### Booking API HTML
   - #### Load Testing
![Load_testing_20mint_HTML](https://github.com/user-attachments/assets/f87b5b7e-c9a0-4725-81d0-99dffeceabd8)

   - #### Stress Testing
![Stress_testing_25k_(StressPoint)HTML](https://github.com/user-attachments/assets/7060ce13-6084-43d2-bea9-0460c9a34920)

### Dmoney API HTML
![html_report](https://github.com/user-attachments/assets/54555eec-3521-4565-b65d-dbd652220637)







 
  
     




