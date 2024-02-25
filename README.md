# Bitcoin Datasets in Real-time.

We utilized our Java code to gather Bitcoin Blocks in \textit{real-time} from the \textit{latest} Block. To interface with the [Blockchain Data API](https://www.blockchain.com/explorer/api/blockchain_api) for collecting real-time Bitcoin Blocks in JSON format, we used HttpURLConnection and [Google GSON](https://github.com/google/gson) 2.10.1.

## Generating Bitcoin datasets
### Installing Libraries

- #### Javac
      $ sudo apt update
      $ sudo apt upgrade
      $ sudo apt install default-jdk

### Executing MainDatasets.java
The output will generate many datasets in the Datasets folder for experimental purposes.

      $ javac -cp /path/to/BitcoinDataset/gson-2.10.1.jar:/path/to/BitcoinDataset MainDatasets.java
      $ java -cp /path/to/BitcoinDataset/gson-2.10.1.jar:/path/to/BitcoinDataset MainDatasets

### Executing MainBitcoinAPI.java
This function collects Bitcoin Blocks in real-time, and we provided many functions to interact with [Bitcoin Data API](https://www.blockchain.com/explorer/api/blockchain_api), including building Merkle tree...

      $ javac -cp /path/to/BitcoinDataset/gson-2.10.1.jar:/path/to/BitcoinDataset MainBitcoinAPI.java
      $ java -cp /path/to/BitcoinDataset/gson-2.10.1.jar:/path/to/BitcoinDataset MainBitcoinAPI

---
## ACKNOWLEDGMENTS 
This work was supported by the Australian Research Council through the Discovery Project under Grant DP200100731.
