# Browser Bug Sandbox

A neat test environment meant for reproducing, simulating, and evaluating various specific browser bugs from bug trackers (like Bugzilla).

### Installation

Clone the repository and install its required dependencies using npm:

```bash
npm install
```

### Running the server

Start the project's development server (uses `nodemon` for auto-restarts upon changes):

```bash
npm start
```

The app will become available at `http://localhost:8080`!

## Included Bug Cases

The main dashboard on `http://localhost:8080` provides links to all available simulated edge-cases, which presently include:
- `Bug 1284488`
- `Bug 1441079`
- `Bug 1542172`
- `Quoted Text` Bug
- Content rendering issues (`htmlresp`, `plain.txt`)
- WebSocket behavior tests

Happy debugging!
