# Test app - Created By Shekhar

Simple Node + Express app that serves a colorful homepage.

Run locally:

```bash
npm install
npm start
# then open http://localhost:5000
```

Build and run with Docker:

```bash
docker build -t test-app .
docker run -p 5000:5000 test-app
```


test-app-manifest for k8s files