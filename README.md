# PowerDeploy

PowerDeploy is a cloud-based architecture and deployment solution designed to streamline the ingestion and data modeling workload. It leverages Databricks, available across various cloud platforms, and Kubernetes to deploy Apache NiFi and DataHub services efficiently.

## Key Features

- **Databricks Workflows and DLTs**: YAML configurations are provided to create Databricks workflows and Delta Lake Tables, simplifying the setup process.
  
- **Simplified Ingestion Notebooks**: Ingestion notebooks are streamlined, focusing only on essential steps such as reading from staging and data cleaning for source ingestions, along with modeling functions for data models.
  
- **True CI/CD Integration**: PowerDeploy ensures continuous integration and delivery by utilizing only the latest commit, facilitating efficient development cycles.
  
- **Apache NiFi Orchestration**: The project includes Apache NiFi with multiple templates, listeners, and other functionalities for seamless orchestration of data workflows.

## Usage

To utilize PowerDeploy effectively, follow these steps:

1. Clone this repository to your local environment.
2. Configure the YAML files according to your specific Databricks workflows and requirements.
3. Explore the provided ingestion notebooks and customize them for your data sources.
4. Implement CI/CD pipelines to automate deployment processes and ensure smooth updates.
5. Utilize Apache NiFi templates and functionalities to orchestrate data workflows efficiently.

## Contributions

Contributions to PowerDeploy are welcome! If you have any improvements, bug fixes, or new features to propose, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to your needs.

## Support

For any questions or issues regarding PowerDeploy, please open an issue on GitHub or contact the maintainers directly.

## Disclaimer

PowerDeploy is provided as-is without any warranties. Use it at your own risk.
