# IPC Debugger A++

A simple simulator to demonstrate inter-process communication:
- Create channels: pipe / msg_queue / shared memory (shm)
- Start simulated processes: producer, consumer, both
- Visual channel blocks and process blocks
- Inject bottleneck, export logs, and alerts (overflow, deadlock, shm conflicts)

## How to run
1. Download or clone the repo.
2. Run: `python src/ipc_debugger.py`

## Files
- `src/ipc_debugger.py` — main app
- `docs/` — screenshots and report files

