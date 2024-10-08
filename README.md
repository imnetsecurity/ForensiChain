# ForensiChain

## Overview

**ForensiChain** is a secure and immutable Blockchain-Based Evidence Chain-of-Custody (CoC) System designed to enhance the integrity, transparency, and reliability of digital evidence handling in cybercrime investigations. By leveraging private blockchain technology, ForensiChain ensures that every action performed on digital evidence—from collection to courtroom presentation—is meticulously recorded, tamper-proof, and easily verifiable by authorized stakeholders.

## Features

- **Immutable Evidence Logging:** Every action on evidence is recorded on the blockchain, ensuring data integrity and preventing tampering.
- **Role-Based Access Control (RBAC):** Secure access for different user roles such as Investigators, Analysts, and Administrators.
- **Smart Contracts:** Automated workflows for evidence creation, transfer, and verification.
- **Secure Off-Chain Storage Integration:** Efficient handling of large evidence files with secure references on the blockchain.
- **Audit Trails and Reporting:** Comprehensive reports and visual dashboards for evidence lifecycle tracking.
- **Real-Time Notifications:** Alerts for custody transfers and unauthorized access attempts.

## Technology Stack

- **Blockchain Platform:** Hyperledger Fabric
- **Smart Contract Language:** Go
- **Backend:** Node.js with Express.js
- **Frontend:** React.js with Material-UI
- **Database:** MongoDB
- **Storage:** AWS S3 for off-chain evidence files
- **Authentication:** JWT (JSON Web Tokens)
- **DevOps:** Docker, Docker Compose, GitHub Actions

## Installation

### Prerequisites

- **Docker:** [Install Docker](https://docs.docker.com/get-docker/)
- **Node.js and npm:** [Install Node.js](https://nodejs.org/en/download/)
- **Git:** [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Clone the Repository

```bash
git clone https://github.com/yourusername/ForensiChain.git
cd ForensiChain
