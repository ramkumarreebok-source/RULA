# RULA
RULA_Ram
## How to Run RULA on Windows

1. Go to Releases and open `v301-final`.
2. Download `RULA_v301_grid_import_constraint_fix.zip` from Assets.
3. Right-click the ZIP and select **Extract All**.
4. Install Python 3.10 or newer if not already installed, and enable Add Python to PATH.
5. Open the extracted folder and double-click `START_RULA_COMMAND_CENTRE300.bat`.
6. Keep the command window open. In your browser, visit http://127.0.0.1:8774/.
7. Open the scenario interface and enter: Solar generation drops by 40%, industrial demand increases by 20%, and maximum grid import capacity is restricted to 10 MW.
8. Expected simplified simulation result: 5 MW unmet demand, with the 10 MW grid import ceiling respected.

**Note:** RULA is a simulation-based research prototype. Additional Python dependencies may be needed depending on the computer's environment.
