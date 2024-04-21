## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Tested Platforms](#tested-platforms)
- [Contributing](#contributing)
- [License](#license)

## Features

- Pings a wide range of IP addresses associated with AWS regions and services
- Calculates the average response time for each IP address
- Displays real-time results during the ping process
- Sorts the IP addresses based on their average response times
- Presents the top 5 fastest IP addresses as the final result

## Prerequisites

- Bash shell (tested on macOS and Linux)
- `ping` command-line utility

## Installation

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/inabakumori/aws-region-latency-tester.git
   ```

2. Navigate to the cloned repository's directory:

   ```
   cd aws-region-latency-tester
   ```

3. Make the script executable by running the following command:

   ```
   chmod +x aws_region_latency_tester.sh
   ```

## Usage

To run the AWS Region Latency Tester script, follow these steps:

1. Open a terminal or command prompt.

2. Navigate to the directory where the script is located.

3. Execute the script by running the following command:

   ```
   ./aws_region_latency_tester.sh
   ```

4. The script will start pinging the IP addresses associated with various AWS regions and services. Real-time results will be displayed in the terminal, showing the average response time for each IP address.

5. Once the script has finished pinging all the IP addresses, it will sort them based on their average response times in ascending order.

6. The top 5 fastest IP addresses will be presented as the final result, indicating the AWS regions with the lowest latency.

## Results

The script will provide real-time results during the ping process, displaying the average response time for each IP address. After the script has completed, it will present the top 5 fastest IP addresses as the final result.

Example output:
```
--------
Top 5 Fastest IPs (Overall):
52.95.255.254 - Avg. Response Time: 12.345ms
52.219.0.0 - Avg. Response Time: 15.678ms
54.231.0.0 - Avg. Response Time: 18.901ms
52.92.0.0 - Avg. Response Time: 21.234ms
54.239.0.0 - Avg. Response Time: 23.567ms
```

Use the information provided in the final result to select the AWS region with the lowest latency for your specific requirements.

## Tested Platforms

This script has been successfully tested on the following platforms:

- macOS
- Linux

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/inabakumori/aws-region-latency-tester).

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more information.
