
Things we need -

```
sudo apt-get update -y
sudo apt-get install build-essential cmake -y

curl https://sh.rustup.rs -sSf | sh
source $HOME/.cargo/env

# think about how to get this onto the box
git clone https://github.com/antiochp/grin.git

cd grin
cargo build

mkdir node1
cp grin.toml node1/.
cd node1

# now tweak grin.toml to enable mining etc.

# start a wallet receiver
# start a mining node
```
