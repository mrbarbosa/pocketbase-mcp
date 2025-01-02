# PocketBase MCP Server

MCP-compliant PocketBase server implementation providing:

- Collection management (CRUD, schema, migrations)
- Record operations 
- User authentication
- Database operations
- File management
- Real-time subscriptions

## Setup

```bash
npm install
npm run dev  # Development
npm run build # Production build
npm start    # Run production
```

## Environment Variables

```env
POCKETBASE_URL=https://your-instance.pockethost.io/
POCKETBASE_ADMIN_EMAIL=admin@example.com
POCKETBASE_ADMIN_PASSWORD=password
POCKETBASE_DATA_DIR=/path/to/pb_data
POCKETBASE_HOOKS_DIR=/path/to/pb_hooks 
POCKETBASE_PUBLIC_DIR=/path/to/pb_public
```