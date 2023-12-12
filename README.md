# Role Prediction in Multiverse

## Overview
Role Prediction in Multiverse is a cutting-edge web application leveraging OpenAI's GPT-3.5 for role prediction within a multiverse context. It integrates a Flask backend with DALL-E image generation and a Vite React frontend, offering a unique and interactive experience.

## Features
- **Role Prediction**: Employs GPT-3.5 for dynamic role prediction in multiverse scenarios.
- **Image Generation**: Uses DALL-E for creating visual representations of predicted roles.
- **Logging and Monitoring**: Implements Loki for logging and Grafana for real-time monitoring.
- **Payment Processing**: Incorporates Stripe for secure and efficient payment transactions.
- **Responsive Frontend**: Developed using Vite and React, ensuring a user-friendly interface.
- **Robust Deployment**: Backend deployed in a VM using Docker, frontend hosted on Vercel.

## Installation

### Prerequisites
- Docker
- Node.js
- Yarn or npm

### Backend
1. Clone the repository.
2. Navigate to the backend folder.
3. Build and run the Docker container:

```
docker build -t role-prediction-backend .
docker run -p 5000:5000 role-prediction-backend
```

### Frontend
1. Go to the frontend folder.
2. Install dependencies:
```
yarn install
```
3. Run the server:


## Usage
Visit `http://localhost:3000` after starting the servers. Follow the instructions to explore roles in the multiverse.

## Contributing
Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License
This project is under the [MIT License](LICENSE.md).

## Acknowledgements
- OpenAI for GPT-3.5 and DALL-E APIs.
- Loki and Grafana for logging and monitoring solutions.
- Stripe for payment processing.
- Vercel for hosting the frontend.

## Contact
For inquiries, please contact [cibimvn@outlook.com](mailto:cibimvn@outlook.com).

