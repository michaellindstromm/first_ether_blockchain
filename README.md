# Private Ethereum Blockchain

---

## To Run

1. Clone the repo
```
git clone https://github.com/michaellindstromm/first_ether_blockchain.git
```

2. Start a local server and take note of the port ie. ```8081```

3. Run the following command with the correct port
```
geth --datadir mychaindata --nodiscover --rpc --rpccorsdomain="http://localhost:8081"
```

---

You will see a button to click that allows you to see the current coinbase.

If you want to mine for more ether, stop the geth node with ```ctrl C``` then run the command
```
geth --datadir mychaindata --nodiscover --rpc --rpccorsdomain="http://localhost:8081" --unlock 0 --mine 1
```
Keep clicking the button and watch the ether rise as you mine for more!



