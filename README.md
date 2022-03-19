# Unit-18--PyChain-Ledger

The application allows the user to input transactions (i.e., sener, receiver, and amount) for a non-specified currency. Initially, the only record showing in the ledger is the "Genesis" block by default, but the user can click "Add Block" to record transactions in subsequent blocks which are added to the ledger. The ledger is displayed at the bottom of the Streamlit application page.

Each line item in the ledger dispalys the transaction data, the creator id (set by default equal to 100 in this application), the hash of the previous block, the timestamp when the block was added, and the nonce for that block. If more difficulty is desired for each block, the sliding bar in the sidebar on the left hand side of the application can be adjusted - the higher the number, the more leading zeroes must be included in the current block's hash, thus increasing the diffulty (and also the nonce).

A screenshot of the Streamlit application is captured below showing multiple transactions recorded on the ledger.

<img width="600" alt="streamlit" src="https://user-images.githubusercontent.com/91380617/159101959-f509ea23-7d30-4a7f-a53e-3a557712422b.PNG">
