# Squads Vanity Keypair generator

This is a script that lets you grind cool addresses for your Squads V4 vaults.

This work is based on this repo: https://github.com/mralbertchen/squads-grinder, credits and big thanks to the creator !

## How to run this ? 

Have Rust installed on your system.

Clone the repo:
```
git clone https://github.com/valentinmadrid/squads-vanity-vault.git .
```

Compile the script:
```
cargo build
```

Run it with the vault Public Key you want:
```
cargo run <YourVaultPubkey>
```
example:
```
cargo run va1
```


