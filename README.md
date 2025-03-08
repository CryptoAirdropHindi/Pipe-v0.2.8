## 1. Download the `pop` binary: This command uses `curl` to download the `pop` binary from the specified URL.
```
curl -L -o pop "https://dl.pipecdn.app/v0.2.8/pop"
```

## 2. Make the `pop` binary executable: This command changes the file permissions to make the `pop` binary executable.
```
chmod +x pop
```

## 3. Create a directory for cache: This creates a new directory where the cache will be stored.
```
mkdir download_cache
```
## 4. Sign up with a referral code: This command runs the `pop` program with the `--signup-by-referral-route` option 
and provides your referral code (`63b754eb97201984`). Make sure to replace this with your actual referral code if needed.
```
./pop --signup-by-referral-route 63b754eb97201984
```

## 5. Start the node with specified configurations: This starts the node with your custom configurations (RAM, disk, cache directory, and public key).
You'll need to replace `<KEY>` with your actual public key and adjust the values for RAM and disk storage as necessary.
```
sudo ./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <KEY> --enable-80-443
```
* `--ram 8`: Allocates 8GB of RAM (adjust based on your machine’s available memory).
* `--max-disk 500`: Limits disk usage to 500GB (adjust as needed).
* `--cache-dir /data`: Specifies the cache directory location.
* `--pubKey <KEY>`: Use your actual public key here (replace `<KEY>`).
* `--enable-80-443`: Enables ports 80 and 443.

Save the file
```
nano ~/node_info.json
```
Ctrl+x to Exit

Node Status
```
./pop --status
```
Check points
```
./pop --points
```
Generate referral
```
./pop --gen-referral-route
```
To Start Next Day, Run THE Start The Node COMMAND

 ---------------------------------------------------------------------------------------------------------------------------

"Great, all set! If you have any questions, don’t hesitate to ask in our Telegram channel."
Or if you'd like something more friendly and engaging:
- Telegram - https://t.me/Crypto_airdropHM
- Youtube - https://www.youtube.com/@CryptoAirdropHindi6
