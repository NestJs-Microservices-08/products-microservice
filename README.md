# Product Microservice

## Development Setup

Follow these steps to set up the development environment:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/NestJs-Microservices-08/products-microservice
    cd products-microservice
    ```

2. **Install Dependencies**:

    ```bash
    npm install
    ```

3. **Environment Configuration**:
    Create a `.env` file based on the `.env.template`:

    ```bash
    cp .env.template .env
    ```

4. **Database Migration**:
    Run Prisma migration to set up your database schema:

    ```bash
    npx prisma migrate dev
    ```

5. **Start the Development Server**:

    ```bash
    npm run start:dev:swc
    ```
