# Security & Identification
USER_NAME="Justin Silvers"
ACCESS_TIER="0"
SILVERS_SHIELD_KEY="your_secure_key"

# Model Config
PRIMARY_LLM="gemini-1.5-pro"
git clone https://github.com/your-repo/agent-name.git
cd agent-name
pip install -r requirements.txt
python main.py --goal "Monitor LiDAR for region X"
# AGENTS.md
## Technical Stack
- Language: Python 3.11+
- Framework: LangGraph / CrewAI
- Deployment: Docker on GCP

## Build Commands
- Setup: `make install`
- Test: `pytest`

## Logic Constraints
- Always validate LiDAR height data against the 2026 baseline before triggering a HookMe event.
