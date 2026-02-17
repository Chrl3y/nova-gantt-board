# Nova Microfinance — Developer Session Gantt

An interactive Gantt chart application for managing developer sessions and project issues during the Nova Microfinance initiative.

## Features

- 📊 Interactive Gantt chart with drag-and-drop task management
- 🔄 Real-time sync with Google Sheets via Apps Script
- 💬 Integrated comments system for task collaboration
- 📜 Full change history tracking
- 🎨 Dark/Light theme support
- 📱 Responsive design for all devices
- 🔐 Session-based authentication

## Getting Started

### Deployment on GitHub Pages

1. **Access the Board**: Visit the live deployment at `https://[your-username].github.io/nova-gantt-board`

2. **Use the Application**:
   - Enter your name to log in
   - Use the admin access key provided by your team
   - Manage issues, drag tasks to adjust timelines
   - Sync changes with the backend

## Configuration

Edit the `CONFIG` object in `index.html` to set:
- `APPS_SCRIPT_URL`: Your Google Apps Script deployment URL
- `SECRET_KEY`: Shared team access key

```javascript
const CONFIG = {
  APPS_SCRIPT_URL: 'https://script.google.com/macros/s/YOUR_DEPLOYMENT_ID/exec',
  SECRET_KEY: 'your-secret-key',
};
```

## Technology Stack

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Backend**: Google Apps Script (optional)
- **Hosting**: GitHub Pages
- **Storage**: Google Sheets + Browser localStorage

## Features Reference

### Priority Levels
- **Critical**: #ef4444 (red) - Must be done immediately
- **High**: #f59e0b (amber) - Important, schedule soon
- **Medium**: #3b82f6 (blue) - Standard priority
- **Enhancement**: #8b5cf6 (purple) - Nice to have
- **Design / Phase 2**: #06b6d4 (cyan) - Future work

### Navigation
- **Details Tab**: Edit issue metadata, dates, owners
- **Comments Tab**: Collaborate with team members
- **History Tab**: View all changes made to an issue

## License

Proprietary - Nova Microfinance Initiative
