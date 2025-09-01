MobileApplication environment configuration

Create a .env file at the project root (same level as pubspec.yaml) using .env.example as a template:

API_BASE_URL=https://your-api-gateway.example.com
WS_URL=wss://your-api-gateway.example.com/ws/notifications
DEBUG=false

Do not commit secrets. The orchestrator/CI will set actual values via environment management.
