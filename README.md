# README

## Solana Blockchain Analysis

This project focuses on analyzing the Solana blockchain to extract and process token transfer data across a range of blocks. By leveraging Solana's RPC API, we fetch transaction data, parse token transfers, and perform data analysis, such as aggregating transfer amounts and visualizing trends over time.

## Getting Started

### Prerequisites

- **Python 3.6** or higher
- Installed Python packages:
  - `requests`
  - `pandas`
  - `matplotlib`

Install the required packages using:

```bash
pip install requests pandas matplotlib
```

### Setting Up an Alchemy RPC URL

To interact with the Solana blockchain, you need access to an RPC endpoint. We recommend using **Alchemy** to obtain a reliable and high-performance Solana RPC URL.

**Steps:**

1. **Sign Up for Alchemy:**

   - Visit the [Alchemy website](https://www.alchemy.com/?r=0285a78c73e7835a) and create a free account.
   - Follow the registration process to set up your account.

2. **Create a New App:**

   - After logging in, navigate to your dashboard.
   - Click on **"Create App"**.
   - **Name your app** and select **"Solana"** as the blockchain.
   - Choose the **network** (e.g., **"Mainnet"**) for your app.

3. **Retrieve Your RPC URL:**

   - Once the app is created, you'll see your Solana RPC URL.
   - Click on **"View Key"** or **"Show URL"** to reveal the full endpoint.
   - **Copy the URL**; you'll need it to configure the project.

**Note:** Ensure you keep your API key secure and do not expose it publicly.

### Configuration

In your Python script, set the `SOLANA_RPC_URL` & `ETHEREUM_RPC_URL` variable to your Alchemy RPC URLs:

```python
SOLANA_RPC_URL = "YOUR RPC URL"
ETHEREUM_RPC_URL = "YOUR RPC URL"
```


### Handling Data

- **DataFrame Operations**: Utilize pandas DataFrame capabilities to manipulate and analyze the data.
- **Visualization**: Use matplotlib to create plots for data visualization.
- **Saving Data**: Export the DataFrame to CSV or Excel files for further analysis or record-keeping.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please feel free to submit a pull request or open an issue on GitHub. Or feel free to [DM me on X](https://x.com/doyle126)

## License

This project is licensed under the MIT License.

---

**Disclaimer:** This project is intended for educational and analytical purposes. Always ensure you comply with the terms of service of the APIs and platforms you use.

---