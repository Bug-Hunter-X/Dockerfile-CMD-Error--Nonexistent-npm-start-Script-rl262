# Dockerfile CMD Error: Missing npm start Script

This repository demonstrates a common Dockerfile error: using `CMD ["npm", "start"]` when `package.json` lacks a `start` script.  The build completes successfully but fails at runtime.  The solution provides the correct `package.json` setup.