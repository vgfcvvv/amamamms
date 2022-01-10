port: 7890
socks-port: 7891
allow-lan: true
mode: Rule
log-level: info
external-controller: :9090
proxies:
  - {name: 🇨🇳 台湾1-三网优化, server: 0105tw.fans8.xyz, port: 80, type: vmess, uuid: 150a7701-f48b-3dab-b6e7-06aa193bf5cf, alterId: 2, cipher: auto, tls: false, network: ws, ws-path: /v2ray, ws-headers: {Host: 0105tw.fans8.xyz}}
