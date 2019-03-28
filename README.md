Use this when you have installed Rust with a method that doesn't use pacman (such as via the method on the official website for Rust).

All it does it is install a package that contains nothing and states that it provies Rust and Cargo (it doesn't, it's up to you to make sure it's in the path).

Steps:
1. Clone the repository. (``git clone https://github.com/HiruNya/rust-fake-arch-package``)
2. Switch to the new folder create. (``cd rust-fake-arch-package``)
3. Install the project. (``makepkg --install``)

I am quite new at making PKGBUILDs so take care when using this.
