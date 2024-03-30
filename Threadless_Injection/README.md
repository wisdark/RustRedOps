# Threadless Injection 🦀

<p align="left">
	<a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/made%20with-Rust-red"></a>
	<a href="#"><img src="https://img.shields.io/badge/platform-windows-blueviolet"></a>
</p>

- [Overview](#overview)
- [Usage](#usage)
- [References](#references)

# Overview

The Threadless Injection technique is very similar to Function Stomping Injection, the difference being that Threadless searches for a memory hole to install the shellcode, removes the trampolin installed in the target function and returns the original bytes. 

# Usage 

You can run with cargo run or the compiled binary directly:
```sh
cargo run
```
```sh
target/release/threadless_injection.exe
```

# References

* https://github.com/CCob/ThreadlessInject