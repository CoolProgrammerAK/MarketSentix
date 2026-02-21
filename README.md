# MarketSentix 👋

MarketSentix is an innovative platform built to transform how stock market news is evaluated. By applying advanced sentiment analysis techniques, MarketSentix delivers meaningful insights into market movements and overall investor sentiment.

## Features

- **Real-time Sentiment Evaluation:** Process and interpret financial news instantly to understand market mood.
- **Interactive Dashboard:** Explore sentiment patterns and historical analytics through a user-friendly interface..
- **Personalized Alerts:** Configure notifications for major sentiment shifts in chosen stocks or industry sectors.

## Prerequisites

- Docker
- Docker Compose

## Running the Project

To run the project using Docker, follow these steps:

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/MarketSentix.git
    cd MarketSentix
    ```

2. **Build the Docker image:**

    ```sh
    docker-compose build
    ```

3. **Run the Docker container:**

    ```sh
    docker-compose up
    ```

4. **Access the application:**

    Open your web browser and navigate to `http://localhost:your_port`.

    ## Setup Environment Variables

    Before running the project, you need to set up the environment variables. Create a `.env` file in the root directory of the project based on the `.env.example` file provided:

    ```sh
    cp .env.example .env
    ```

    Edit the `.env` file to configure the necessary environment variables.
