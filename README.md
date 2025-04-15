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
3. Install the dependencies
    ```bash
    uv install
    ```
4. Activate virtual environment
   ```bash
   chmod +x ./.venv/bin/activate
   source ./.venv/bin/activate
   ```
4. Run the program
    ```bash
    adk web
    ```
5. Test at [http://localhost:8000](http://localhost:8000)