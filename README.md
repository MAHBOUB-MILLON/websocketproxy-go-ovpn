# websocketproxy-go-ovpn
Reserve proxy websocket in GO for openvpn
# websocketproxy-GO

Reserve proxy websocket in GO 

# FAST PROXY STABLE HTTP

# INSTALLATION

• First install openvpn tcp 1194 then run proxy 

```

apt install golang-go

```

```

wget https://raw.githubusercontent.com/MAHBOUB-MILLON/websocketproxy-go-ovpn/main/proxy.go

```

```

chmod +x proxy.go

```

```

go run proxy.go

```

# • HTTP PROXY BASED ON OPENVPN

• PORT 80

you can use screen command to run proxy

# PAYLOAD HTTP CUSTOM 

```

POST / HTTP/1.1[crlf]Host: bughost.com[crlf]Expect: 100-continue[crlf][crlf]GET- / HTTP/1.1[crlf]Host: domaincloud.com [crlf]Upgrade: Websocket[crlf][crlf]

```
