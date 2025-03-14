# JMeter API & Performance Testing 
## Description
This repository hosts **JMeter** test plans for two different API scenarios. The **Booking API (booking.jmx)** is intended for performance testing, including load and stress testing, to analyze the system's reliability and capacity. The **Dmoney API (dmoney.jmx)** is designed for functional testing, ensuring the proper execution of financial operations like deposits, transfers, and payments.

## Prerequisites
- **Apache JMeter** for performance and functional testing
- **Java (JDK 17)** for running JMeter and tests
   
## How to run this project
- ### Clone the Repository
     - ```git clone https://github.com/Naila-Nur99/jmeter-api-performance-testing.git ```
     - ```cd jmeter-api-performance-testing ```
 
- ### Running the Booking API Test (Performance Test)
   - #### Steps
      - Open booking.jmx in JMeter.
      - Run tests for 5, 10, and 20 minutes.
      - Review the HTML report for the results.
      - If the load test is successful, gradually increase the number of users to identify the bottleneck (stress test).
      - Generate an HTML report and save results in booking-api-test-report.xlsx.
        
- ### Running the Dmoney API Test (Functional Test)
   - #### Steps
      - Open dmoney.jmx in JMeter.
      - Make sure the deposit.csv, sendMoney.csv, and payment.csv files are available.
      - Check authentication tokens and account setups.
      - Run the test to validate financial transactions.
## Results & Reports
### Booking API
   - #### Load Testing (Report Summary & Report Statistics)
![Load_testing_20mint_HTML](https://github.com/user-attachments/assets/f87b5b7e-c9a0-4725-81d0-99dffeceabd8)

   - #### Stress Testing (Report Summary & Report Statistics)
![Stress_testing_25k_(StressPoint)HTML](https://github.com/user-attachments/assets/7060ce13-6084-43d2-bea9-0460c9a34920)

### Dmoney API
   - #### Functional Testing (Report Summary & Report Statistics)
![html_report](https://github.com/user-attachments/assets/54555eec-3521-4565-b65d-dbd652220637)







 
  
     




