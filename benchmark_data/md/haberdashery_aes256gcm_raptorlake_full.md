[//]: # (@generated)
| operation     | cycles   |
|---------------|----------|
| init          | 130.5045 |
| aad empty     | 24.7589  |
| encrypt empty | 24.7392  |
| decrypt empty | 25.0923  |

| bytes | aad    | encrypt | decrypt |
|-------|--------|---------|---------|
| 256b  | 0.3294 | 0.8290  | 0.7273  |
| 16kb  | 0.2669 | 0.6343  | 0.6158  |
| 64kb  | 0.2664 | 0.6327  | 0.6141  |
| 1mb   | 0.2661 | 0.6318  | 0.6139  |

| metadata  |                                                                  |
|-----------|------------------------------------------------------------------|
| algorithm | aes256gcm                                                        |
| cpu       | IntelRaptorlake (06_b7H)                                         |
| library   | haberdashery                                                     |
| primitive | aead                                                             |
| profile   | raptorlake                                                       |
| runs      | 5                                                                |
| version   | cc1766c807c472404ad2371eef7cad7c8982a757d3e3a64f1ebf79a1e679996b |
