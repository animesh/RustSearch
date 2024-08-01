# RustSearch
command line utility to seach for files containing some string

## test

module spider Rust/1.76.0-GCCcore-13.2.0
git clone https://github.com/animesh/RustSearch
cd RustSearch/
rustup default stable
cargo run Cargo.toml
echo "Check it out" > test.txt
mkdir test
cp test.txt test
./target/debug/RustSearch "Check"
You entered: Check
/cluster/projects/nn9036k/scripts/RustSearch/test.txt: Check it out
/cluster/projects/nn9036k/scripts/RustSearch/test/test.txt: Check it out

