https://etherscan.io/address/0x70e2b6d1dc931bbe6cd7d916c31e6287e5a16793#code

HECO testnet:

Token Address:  0x059Eb1cAa1b9837c9a747dF48d5c8F226070a68a
Vest Contract:  0x3e4c42557fD001CF537F8ec10113960B1aF899B4


1) contructor:
constructor (address token, uint256 start, uint256 cliffDuration, uint256 duration, bool revocable)
token:         0x059Eb1cAa1b9837c9a747dF48d5c8F226070a68a (token address)
start:         3517668                                    (from which block)
cliffDuration: 1000                                       (for these blocks no token is ditributed)
duration:      100000                                     (how many block to ditributed all money)
revocable:     true                                       (revocable or not)


2) Set addresses
setBeneficiaries(address[] memory addresses, uint256[] memory amounts)

addresses: 
["0xa22980c9143722f5A8F72ab14D6844CABF450337", "0x827997b4c822ade17ED3Ca484Ca5a894673BBde0", "0xAcBb625714b2A9db4Ae369E69e55E6Be2336De32"]
amounts: 
["10000000000000000000000", "10000000000000000000000", "10000000000000000000000"]
