```powershell
cargo install rustlings
cd C:/Users/phili/OneDrive/Documents/Programmation/rust/02_xt
rustlings init
rename-item ./rustlings ./000_rustlings
cd 000_rustlings
```

## If OneDrive
Delete (if any)  : target/
Create file      : ./cargo/config.toml
Add this section :

```toml
[build]
target-dir = "C:/Users/phili/rust_builds/Documents/Programmation/rust/02_xt/000_rustlings"
```

## Go !
`code .`
Open terminal (`CTRL+ù`)
`rustlings`
Open the editor on the exercice, make your changes, `CTRL+S`