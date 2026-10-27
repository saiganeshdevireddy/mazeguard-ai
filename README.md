# MazeGuard AI

MazeGuard AI is an advanced MVP for safe investigation of suspicious digital content. It combines:

- local AI analysis
- rule-based risk scoring
- six-agent security architecture
- isolated sandbox execution
- private browser session support
- cryptographic metadata protection
- blockchain-style audit hash integrity
- risk meter and voice warning indicators

## Features

- URL phishing and suspicious-link analysis
- suspicious file analysis (PDF, zip, executable, script, document-like content)
- Docker sandbox integration for isolated processing
- browser privacy session mode flag for safer browsing workflows
- cryptographic encryption for sensitive metadata
- event hashes for audit integrity
- voice warnings for risk escalation
- frontend dashboard with risk meter and agent results

## Quick start

1. Create a virtual environment
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

3. Run the backend
   ```bash
   uvicorn backend.app:app --host 0.0.0.0 --port 8000 --reload
   ```

4. Open the dashboard
   ```text
   http://localhost:8000/
   ```

## Risk levels

- LOW: 0-29
- UNCERTAIN: 30-59
- HIGH: 60-100

## Architecture summary

- Sentinel: threat detection and reputation checks
- Sandbox Agent: isolated execution and environment controls
- Analyzer: deep file and behavior review
- Informer: plain-language explanations and warnings
- Cryptographic Guard: encryption, integrity, access protection
- Orchestrator Guardian: final decision and policy enforcement

## Security notes

- Browser private tabs are privacy controls, not full malware protection.
- Real sandboxing requires OS or container isolation.
- Blockchain is used only for selected tamper-evident audit hashes, not raw sensitive data.
- Local AI analysis should be treated as advisory and combined with deterministic checks.

## License

This project is provided for research and educational use. It should be used with proper security validation before production deployment.
