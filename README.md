# Data Parsing
Miscellaneous repository for various data parsing from various sources
### mining_data
* Confluxscan
   * `parseConfluxscan*.py` - pull data from Confluxscan API
* Mining metrics
   * `convertToCSV` - convert JSON objects from various sites to CSV

### github_data
* Github
   * `index.js` - pull Dev + Repo information from Github
   * `devAnalysis.py` - parse Dev data from github and return metrics

### bitquery_data
* Bitquery (GraphQL, transaction data)
   * `inefficientGetContractCreation.js` - cycle through all transactions to find contract creation (method for GraphQL API not available)
   * `tokenTransfers.js` - pull token data from bitquery
