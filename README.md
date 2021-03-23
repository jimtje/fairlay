# Fairlay API Client

```bash
pip install fairlay
```



```python
import fairlay
```



## Public Client

```python
client = fairlay.FairlayPublicAPI()

client.get_comps("soccer")

client.get_markets(Cat="basketball")
```



## Private Client

```python
client = fairlay.fairlayPrivateAPI(id=1000000, apiaccountid=1, pubkeypem='publickey.pem', privkeypem='privkey.pem')

client.get_me()

client.get_markets_orderbook(Cat="baseball")


```


