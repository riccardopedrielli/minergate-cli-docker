# MinerGate-cli

Docker image that runs minergate-cli.

For more informations see the [MinerGate website](https://minergate.com/).

## Usage

```
docker run vortex/minergate-cli
```

The following variables can be set.

| Variable | Description                             | Default              |
|----------|-----------------------------------------|----------------------|
| USERNAME | Your account email address              | My email, change it. |
| COIN     | Coin symbol                             | xmr                  |
| THREADS  | Number of cpu threads to use for mining | 2                    |

These are the coins you can mine.

| COIN |
|------|
| bcn  |
| xmr  |
| qcn  |
| xdn  |
| fcn  |
| mcn  |
| aeon |
| dsh  |
| inf8 |
