# AgriPilot AI

## Autonomous Farm Operations & Intelligent Resource Management Platform

AgriPilot AI is a production-oriented, AI-powered agricultural management system. It bridges real-time weather forecasts, soil health data, crop growth stages, equipment availability, and field operations to formulate feasible schedules and autonomously respond to unexpected weather events, machine breakdowns, and resource constraints across multiple farms.

---

### Core Highlights

1. **Autonomous Rescheduling & Constraint Engine**: Detects weather changes (e.g., unexpected rain) or equipment breakdowns, computes trade-offs, generates alternative schedules, and enforces human-in-the-loop approval.
2. **Multi-Farm Resource Coordination**: Coordinates shared machinery (tractors, harvesters, sprayers) and workers across distinct farm holdings with travel constraints and double-booking prevention.
3. **Weather Intelligence**: Real-time forecast integration via Open-Meteo with spray suitability indices, severe weather alerts, and caching.
4. **Crop Health & Diagnostics**: Photo submissions with AI symptom analysis, confidence ratings, and agronomist review workflows.
5. **Interactive Mapping**: Farm and field boundary visualization powered by Leaflet & OpenStreetMap.
6. **AI Agricultural Assistant**: Conversational assistant armed with permission-bounded tools to query farm status, inspect schedules, and draft tasks.
7. **Production-Grade Architecture**: Monorepo with React 18, Vite, TypeScript, Tailwind CSS, Node.js, Express, Prisma ORM, and Docker Compose.

---

### Getting Started

```bash
# 1. Install dependencies across workspaces
npm install

# 2. Start the API backend
npm run dev:api

# 3. Start the Web frontend
npm run dev:web
```

Access the web interface at `http://localhost:5173`.
Access the API at `http://localhost:4000/api/v1`.
