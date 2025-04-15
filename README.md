# POC for audit document checking

Program developed using **Google Agent Development Kit** to assist in document readiness check.

## How to run

1. Clone the repository
    ```bash
    git clone git@github.com:bkmehata/adk_audit_poc.git
    ```
2. Install uv package manager
    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```
3. Move inside the folder
   ```bash
   cd adk_audit_poc
   ```
4. Install the dependencies
    ```bash
    uv sync
    ```
5. Activate virtual environment
   ```bash
   chmod +x ./.venv/bin/activate
   source ./.venv/bin/activate
   ```
6. Get your key at [Google AI Studio](https://aistudio.google.com/apikey) Add you key to `audit_agent/.env`

6. Run the program
    ```bash
    adk web
    ```
7. Test at [http://localhost:8000](http://localhost:8000)