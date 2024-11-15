# Hello World NServiceBus

📚 A repository to learn **[NServiceBus](https://particular.net/nservicebus)**, a .NET library for building distributed systems with message-based communication.

[![wakatime](https://wakatime.com/badge/github/GuilhermeStracini/hello-world-nservicebus.svg)](https://wakatime.com/badge/github/GuilhermeStracini/hello-world-nservicebus)
[![Maintainability](https://api.codeclimate.com/v1/badges/e506f6d5e6ef45e72ca2/maintainability)](https://codeclimate.com/github/GuilhermeStracini/hello-world-nservicebus/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/e506f6d5e6ef45e72ca2/test_coverage)](https://codeclimate.com/github/GuilhermeStracini/hello-world-nservicebus/test_coverage)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/7de4e8d7da0646da87282dbdf9c83946)](https://app.codacy.com/gh/GuilhermeStracini/hello-world-nservicebus/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

---

## Overview

This repository provides examples and best practices for using NServiceBus to build robust, distributed, and scalable applications. It covers core concepts like messaging patterns, reliable communication, and integration with various transport and persistence mechanisms.

---

## Features

- **Message-Based Communication**:
  - Learn to implement asynchronous, decoupled communication using commands, events, and messages.

- **Transport Integration**:
  - Examples using popular transports like RabbitMQ, Azure Service Bus, and MSMQ.

- **Persistence**:
  - Implement message persistence with databases like SQL Server or NoSQL stores like MongoDB.

- **Reliability**:
  - Understand retry policies, error handling, and message auditing.

- **Scalability**:
  - Learn to scale services effectively with NServiceBus tools and configuration.

---

## Getting Started

### Prerequisites

- **.NET SDK**: Install the latest version from [Microsoft's .NET site](https://dotnet.microsoft.com/).
- **NServiceBus NuGet Package**: Install the [NServiceBus library](https://www.nuget.org/packages/NServiceBus) for your transport of choice.

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GuilhermeStracini/hello-world-nservicebus.git
   cd hello-world-nservicebus
   ```

2. **Install Dependencies**:
   ```bash
   dotnet restore
   ```

3. **Run the Project**:
   ```bash
   dotnet run
   ```

4. **Explore Examples**:
   - Look at individual projects within the solution to see different use cases and configurations.

---

## Useful Resources

Explore these links to deepen your knowledge of NServiceBus and its ecosystem:

- [Official NServiceBus Documentation](https://docs.particular.net/nservicebus/)
- [NServiceBus Sample Applications](https://docs.particular.net/samples/)
- [NServiceBus on GitHub](https://github.com/Particular/NServiceBus)
- [Understanding Reliable Messaging with NServiceBus](https://particular.net/blog/reliable-messaging)

---

## Contribution

Contributions are welcome!  
Feel free to fork this repository, open issues, or submit pull requests to enhance examples or add new features.

---

## License

This project is licensed under the [MIT License](LICENSE).

---
