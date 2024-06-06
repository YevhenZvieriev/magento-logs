# Magento 2 Log Management Script

## Overview
Simplify and streamline your Magento 2 log management with this powerful bash script. This project, created by a Magento engineer, offers an easy-to-use interface for viewing, tailing, and searching logs from your Magento 2 project in real time. Enhance your debugging and monitoring capabilities with color-coded log entries for better readability and quick issue identification.

## Features

* Tail Logs in Real-Time: Effortlessly tail all or specific log files directly from your Docker container, with color-coded output for ERROR, WARNING, INFO, and DEBUG messages.
* View Log Files: Quickly view the content of specific log files without leaving the command line.
* Search for Errors: Automatically search for and highlight ERROR, FATAL, CRITICAL, WARNING, INFO, and DEBUG messages in your log files.
* Customizable Options: Easily configure the path to your log files and the Docker container name, tailored to fit your specific setup.
* Interactive Menu: A user-friendly interactive menu to choose from various log management operations.

## Usage
![Screenshot from 2024-06-06 20-33-03](https://github.com/YevhenZvieriev/magento-logs/assets/43544955/97cda864-b70a-424d-b850-a6d09798113e)

## 1. View existing log files:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/e23d259c-0565-4e35-9514-ab926eef91ae


## 2. Display the content of any specific log file directly from the Docker container:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/8290daec-497b-46e7-9dcd-e5ed80571ef4


## 3. Search Errors: Automatically search and highlight errors and warnings across all log files:
   
https://github.com/YevhenZvieriev/magento-logs/assets/43544955/6dc305b8-5f2b-4b89-8c84-9fa3d231952c


## 4. Tail Logs: Monitor logs in real-time with an option to view all logs or only error logs:


https://github.com/YevhenZvieriev/magento-logs/assets/43544955/79a454b5-d6a7-4eba-bd44-491e2c09ea82


   
## 5. Configure Options: Set custom log file paths and container names according to your environment setup:


https://github.com/YevhenZvieriev/magento-logs/assets/43544955/e778f23e-0291-478c-a420-ba39df9b5cba


### This functionality will be useful for those with log files stored in a folder other than the default, so you can change it to suit your needs. Also, for your convenience, if you don't want to change the path or container name, press Enter to keep the current value
## Installation

### Download the bash script inside the `bin` folder of your Magento 2 project

```
curl -O https://raw.githubusercontent.com/YevhenZvieriev/magento-logs/main/bin/log
```

Now you can make the bash script executable:

```
chmod +x ./log
```

## How to use
1. Run the script:
```
./bin/log
```
2. Follow the on-screen menu to select the desired action.

## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
