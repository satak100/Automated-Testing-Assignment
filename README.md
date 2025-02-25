📌 Overview
This repository contains an offline assignment on Automated Load Testing using Apache JMeter for performance evaluation of web applications. The assignment was conducted as part of the Department of Computer Science and Engineering, BUET.

Apache JMeter is a powerful open-source tool used for load testing, performance testing, and stress testing of web applications. In this assignment, JMeter is used to simulate 50 and 100 concurrent users with a ramp-up time of 100 seconds, measuring key performance metrics such as response time, throughput, and data transmission.

📊 Tested Web Applications
The following web applications from CSE, BUET were tested:
1️⃣ Moodle → https://cse.buet.ac.bd/moodle
2️⃣ Home → https://cse.buet.ac.bd/home
3️⃣ Notice Section → https://cse.buet.ac.bd/home/notice

🔍 Test Plan & Methodology
✅ Sample Sizes: 50 and 100 users
✅ Ramp-Up Time: 100 seconds
✅ Assertions & Listeners: Duration assertions were applied to observe both successful and failed requests.
✅ HTTP(S) Test Script Recorder: Used to monitor HTTP requests and responses.
✅ Performance Metrics Analyzed:

Shortest, longest, and average execution time
Average throughput, data reception, and data transmission
📑 Deliverables
✔️ Word Report (<yourID>_Assessment.docx) - Comparative analysis of execution times and throughput.
✔️ JMeter Test Plan (<yourID>_testPlan.jmx) - Configuration for test execution.
✔️ CSV Result File (<yourID>_result.csv) - Raw test results.
✔️ HTML Report (<yourID>_html.zip) - Detailed test analysis.

⚡ How to Run the Test Plan?
1️⃣ Install Apache JMeter (Download from here).
2️⃣ Open JMeter and load <yourID>_testPlan.jmx.
3️⃣ Run the test plan and verify results in CSV & HTML reports.
4️⃣ Analyze response time, throughput, and error rates.

🔗 References
Apache JMeter Documentation
JMeter Beginner Guide
