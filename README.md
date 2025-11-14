# ARC Control

A native Android/iOS application showcasing multi-chain crypto functionality (ArcEVM, Solana, Noble and all supported CCTP enabled networks) and an interactive price chart with technical indicators and AI insights. The app integrates on-chain data (balances, transfers/bridging) and a candlestick chart that can fetch OHLCV data, compute indicators (RSI, MACD, SMA), and render AI-generated annotations on top of the chart.

You can easily check all USDC/EURC balances across all networks and shift it around with a single tap
Furthermore you can use the integrated Chart to investigate pricechart along with an easy-to-use UI and Akash powered Chart Insights

## Highlights

- **Multi-chain integrations**
  - EVM and Solana token pairs via Moralis OHLCV API
  - EVM chains (e.g., Sepolia/Testnet) with ERC-20 balance queries
  - CCTP bridge flows with attestation polling

- **AI Insights**
- Chart Analyzer with easy-to-adjust technical Indicators: SMA, RSI, MACD and stochastic oscillator 
- Adjust the indicators, and send the dataset to all supported Akash models  chatapi.akash.network
  - Sends the currently loaded range, candles, and indicators to an Akash 235B LLM
  
    Download link
  - https://nride.network/wp-content/uploads/ArcControl_v004.apk

  Web Version (only Price Chart Analysis)
  https://arccontrol2.vercel.app/

  - Parsed markers and trends are rendered on the chart; the top panel shows the AI summary and lists markers/trends

