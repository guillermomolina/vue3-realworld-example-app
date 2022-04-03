# Create network

```bash
$ docker create network conduit_network
```

Then added to devcontainer.json

```json
	"runArgs": [
		"--name=conduit_frontend",
		"--network=conduit_network",
		"--hostname=frontend"
	]
```