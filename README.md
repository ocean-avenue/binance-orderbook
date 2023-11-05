# binance-orderbook
📉📈 Visualize binance order book data fetched from API

Should support `binance`, `binance.future` and `binance.us`, config sample:
```
const config = {
  symbol: "btcusdt",
  depthUrl: "https://fapi.binance.com/fapi/v1/depth",
  depthLimit: "1000",
  wsAddress: "wss://fstream.binance.com/ws",
  wsSpeed: "500ms",
}
```

See demoe here: https://binance-orderbook.web.app/
