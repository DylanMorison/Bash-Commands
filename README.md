# Bash-Commands
Who is listening on a given TCP port on Mac OS X?
```bash
sudo lsof -i -P | grep LISTEN
```

To kill the PID:
```bash
sudo kill -9 <PID>
```
