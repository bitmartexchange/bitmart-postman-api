# Changelog


#### 2023-08-31
- New spot public market v3 endpoints
    - <code>/spot/quotation/v3/tickers</code> Get Ticker of All Pairs (V3)
    - <code>/spot/quotation/v3/ticker</code> Get Ticker of a Trading Pair(V3)
    - <code>/spot/quotation/v3/lite-klines</code> Get Latest K-Line (V3)
    - <code>/spot/quotation/v3/klines</code> Get History K-Line (V3)
    - <code>/spot/quotation/v3/books</code> Get Depth(V3)
    - <code>/spot/quotation/v3/trades</code> Get Recent Trades(V3)

---

#### 2023-07-22
- New endpoints for trading
    - <code>/contract/private/submit-leverage</code>Submit Leverage (SIGNED)

---

#### 2023-07-07
- New endpoints for Sub-Account
    - <code>/account/contract/sub-account/main/v1/transfer-list</code>Get Sub-Account Transfer History (For Main Account）(KEYED)
    - <code>/account/contract/sub-account/v1/transfer-history</code>Get Account Futures Asset Transfer History (For Main/Sub Account）(KEYED)


---

#### 2023-06-20
- New endpoints for futures Sub-Account
    - <code>/account/contract/sub-account/main/v1/sub-to-main</code>Sub-Account to Main-Account (For Main Account) (SIGNED)
    - <code>/account/contract/sub-account/main/v1/main-to-sub</code>Main-Account to Sub-Account (For Main Account) (SIGNED)
    - <code>/account/contract/sub-account/sub/v1/sub-to-main</code>Sub-Account to Main-Account (For Sub-Account) (SIGNED)
    - <code>/account/contract/sub-account/main/v1/wallet</code>Get Sub-Account Futures Wallet Balance (For Main Account) (KEYED)
- New endpoints for futures order
    - <code>/contract/private/get-open-orders</code>Get All Open Orders (KEYED)

---

#### 2023-05-19
- Added Sign pre-request script
- Added `BitMart Pro API` Environments config
- Added `Spot`, `Furutes` collections
