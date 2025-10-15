# CRM Data Enrichment Bot

## Project Overview
This project implements a Robotic Process Automation (RPA) bot built with UiPath Studio to automate CRM data enrichment. The automation bot eliminates manual data entry by scraping and integrating customer data from Apptivo CRM and Crunchbase, ensuring accurate, complete, and up-to-date customer records. This boosts sales productivity and data quality for targeted marketing campaigns.

## Features
- Automated data enrichment for CRM systems using UiPath RPA.
- Web scraping integration for Apptivo CRM and Crunchbase to extract social media and website data.
- Parallel execution capability to handle large volumes of customer records efficiently.
- Enhanced data accuracy, reducing human error and manual workload.
- Seamless integration with UiPath Orchestrator for scalable automation management.

## Tools Used
- UiPath Studio (RPA development platform)
- Google Chrome (web scraping browser)
- Apptivo CRM (customer management system)
- Crunchbase (company and contact data source)
- UiPath Orchestrator (automation orchestration and monitoring)

## Getting Started

### Prerequisites
- UiPath Studio installed (version XX or later)
- UiPath Robot and Orchestrator set up for deployment (optional, for scaling)
- Access credentials to Apptivo CRM and Crunchbase APIs or web interfaces

### Installation
1. Clone or download the repository.
2. Open the .xaml workflow files using UiPath Studio.
3. Configure input parameters such as CRM URLs, user credentials, and API keys.
4. Publish workflows to Orchestrator or run locally from UiPath Studio.

### Usage
- Run the `Main.xaml` workflow to start the automation.
- Monitor job progress and logs via UiPath Studio or Orchestrator.
- Use queues and retry mechanisms to handle exceptions and ensure data integrity.

## Project Structure
- `Workflows/` - Contains UiPath `.xaml` files for various automation sequences.
- `Config/` - Holds configuration files including credentials and URLs.
- `Logs/` - Directory for logging automation run details.
- `README.md` - Project documentation (this file).

## Contributing
Contributions, issues, and feature requests are welcome. Please fork the repository and create a pull request with your modifications.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.
