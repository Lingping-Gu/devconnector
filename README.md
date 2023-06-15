# DevConnector

> Social network for developers

This is a small social network app that includes authentication, profiles and forum posts.

### Install server and client dependencies

```bash
npm install
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```

### Build for production

```bash
cd client
npm run build
```

### Local Running

After running a build in the client, cd into the root of the project.  
And run...

Linux/Unix

```bash
NODE_ENV=production node server.js
```

Windows Cmd Prompt or Powershell

```bash
$env:NODE_ENV="production"
node server.js
```

Check in browser on [http://localhost:10000/](http://localhost:10000/)
