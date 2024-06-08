# Magento 2 Log Management Script

## Overview
Simplify and streamline your Magento 2 log management with this powerful bash script. This project, created by a Magento developer for Magento developers, offers an easy-to-use interface for viewing, tailing, and searching errors in your log files from your Magento 2 project in real time. Enhance your debugging and monitoring capabilities with color-coded log entries for better readability and quick issue identification.

## Features

* Tail Logs in Real-Time: Effortlessly tail all or specific log files directly from your Docker container, with color-coded output for ERROR, WARNING, INFO, and DEBUG messages.
* View Log Files: Quickly view the content of specific log files without leaving the command line.
* Search for Errors: Automatically search for and highlight ERROR, FATAL, CRITICAL, WARNING, INFO, and DEBUG messages in your log files.
* Customizable Options: Easily configure the path to your log files and the Docker container name, tailored to fit your specific setup.
* Interactive Menu: A user-friendly interactive menu to choose from various log management operations.

## Usage

![Screenshot from 2024-06-08 10-22-41](https://github.com/YevhenZvieriev/magento-logs/assets/43544955/be8781af-0c6b-4b8e-88fd-2b672a19ced7)

## 1. View existing log files:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/861f0ec0-a40d-47ed-892b-4f7f7c77e55e

## 2. Display the content of any specific log file directly from the Docker container:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/ba09e155-5f64-41c2-b880-7227dd9fab2e

## 3. Search Errors: Automatically search and highlight errors and warnings across all log files:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/36705b45-c757-46ed-b50c-c9ba26c1f8f8

## 4. Tail Logs: Monitor logs in real-time with an option to view all logs or only error logs:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/5a572944-1d16-4840-86bb-76d2b61dccec

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/114418a4-28d1-4225-87da-dea258cdb4ab
   
## 5. Configure Options: Set custom log file paths and container names according to your environment setup:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/2749050b-5a7c-4e18-9582-f6a09f945295

#### This functionality will be useful for those with log files stored in a folder other than the default, so you can change it to suit your needs. Also, for your convenience, if you don't want to change the path or container name, press `Enter` to keep the сurrent value.

#### For example, your log files are found in the `/var/log/Amasty/` folder, you can easily view them using this option:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/3743fbef-1ea5-4027-8a9d-031a089d858a


## 6. Possibility to execute `bin/log` with arguments

For example, use `bin/log --tail cron.log system.log` OR `bin/log -t system.log cron.log` to shorten, you can monitor logs in real-time for two or more log files.

Also, if your log files are found in the `/var/log/Amasty/` folder using `bin/log -t Amasty/some.log Amasty/some2.log` OR `bin/log --tail Amasty/some.log Amasty/some2.log` you can easily view them:

https://github.com/YevhenZvieriev/magento-logs/assets/43544955/1c9235cc-171f-464c-9ae3-9beb3a6df90e

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

Given the length of the script, I've provided comments to help people understand if they would like to contribute.

## License

This project is licensed under the MIT License.
