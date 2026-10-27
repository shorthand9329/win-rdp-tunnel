# win-rdp-tunnel

windows-latest runner: net user runneradmin -> enable RDP -> cloudflared tcp://127.0.0.1:3389

Connect: cloudflared access tcp --hostname <trycloudflare-url> --url 127.0.0.1:13389  (user: runneradmin / 1qaz@WSX)
