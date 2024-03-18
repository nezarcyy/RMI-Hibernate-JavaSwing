# Exploring Remote Method Invocation (RMI) in Distributed Systems

## Overview
This repository contains the source code and explanation for an article exploring the concepts of Remote Method Invocation (RMI) in distributed systems. The article delves into the theoretical foundations of RMI and demonstrates its practical implementation through the ServerMachine and ClientMachine projects.

## Article Link
[Read the full article on Medium](https://medium.com/@n-simh/understanding-rmi-an-insight-into-remote-method-invocation-22bb4496f263)

## Contents
- ServerMachine: Explanation and code breakdown for the ServerMachine project.
- ClientMachine: Explanation and code breakdown for the ClientMachine project.
- Images: Visual aids used in the article.

## How to Use
1. Clone the repository to your local machine.
2. Navigate to the respective project directories (`ServerMachine` and `ClientMachine`) to access the source code and explanations.
3. Ensure you have Java and MySQL installed on your system.
4. Set up the MySQL database by importing the provided schema (`schema.sql`).
5. Update the Hibernate configuration file (`hibernate.cfg.xml`) with your MySQL database credentials.
6. Run the `ServerMachine` project to start the RMI registry and expose the services.
7. Run the `ClientMachine` project to connect to the ServerMachine and interact with the remote services.
8. Explore the code and accompanying explanations to gain a deeper understanding of RMI in distributed systems.

## Feedback
If you have any feedback or suggestions, feel free to open an issue or pull request in this repository. Your contributions are greatly appreciated!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
