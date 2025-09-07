# Load Testing and Stress Testing Using JMeter

This project simplifies the two testing methodologies performed on a public server, where users can sign up to create their own bookings

# Technology Used

- Apache JMeter 5.6.3
- Java JDK 17+
- nodejs
- newman

# How to run tests in GUI Mode

- Open ApacheJmeter
- Open booking.jmx 
- Configure threads, ramp-up, and duration as needed
- Run the test and view results in listeners

# How to run tests in Non-GUI Mode

- Go to the Apache bin folder
- Open a terminal in VS Code and put the following command
- jmeter -n -t "booking.jmx" -l "booking.jtl" -e -o ".\Test Report"
- After execution, open index.html file

# Load Test HTML Report

<img width="1350" height="635" alt="image" src="https://github.com/user-attachments/assets/f668a3b8-efa1-4c50-a5fa-58ee32fe49cf" />

<img width="1351" height="632" alt="image" src="https://github.com/user-attachments/assets/d6c63fc8-68e6-431d-a99f-de8a3932df32" />

# Stress Test HTML Report

<img width="1350" height="630" alt="image" src="https://github.com/user-attachments/assets/41d536b8-db2f-4187-a47b-187d6a72976d" />

<img width="1349" height="629" alt="image" src="https://github.com/user-attachments/assets/0f70a03b-e30d-4537-a04b-9939c50bd0aa" />




 
