# Sample backend and frontend

Assumes that you have Node.js and uv installed.

To run on your machine:

1. Clone this repository and navigate to project root.

2. Install dependencies for backend with uv:

    ```bash
    cd backend
    uv sync
    ```

    and activate the virtual environment (depends on your OS):

3. Start the backend server:

    ```bash
    flask --app server run --debug
    ```

4. Open a new terminal and navigate to the frontend directory:

    ```bash
    # In a new terminal window that is in project root
    cd ./frontend-next
    ```

5. Install dependencies for frontend with npm:

    ```bash
    npm install
    ```

6. Start the frontend:

    ```bash
    npm run dev
    ```

See frontend in action at `http://localhost:3000`.
