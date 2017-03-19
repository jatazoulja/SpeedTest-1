# Speedtest stats
This tool does every 5 minutes a speedtest and add it to a database.  
You can seed the results in a webinterface which updates itself in realtime.

#### NOTE: Requires nodejs (+npm) and python (+pip)

```bash
pip install speedtest-cli
npm install
npm run build
npm run start-p
```

Webinterface is running on port 3000 and realtime api on port 3001.