# What is Radiator OS ?
The operating system for everyone. Software developers, System Admins, Ethical Hackers, Gamers, Content Creators, UI/UX Designers, Casual Computer Users. Anyone can use Radiator OS! It's a ligthweight, secure and Indipendent Operating system developed by Venkatesh Mishra in co-operation with Netwrk-3 Inc. 

# Why use Radiator OS ?
As mentioned earlier Radiator is lighweight OS, which means it used less computer resource to function and gives other software more resources to function. This also means that Radiator can give better performence than other Operating Systems on Older or Newer Hardware. It has a memory decreasing Algorithm specificly made for this purpose. Also mentioned earlier was the fact that Radiator OS is secure. It has a file scanning process written in Rust and also a custom made firewall by Netwrk-3.
Since the OS is open source, developers can see the source code and patch possible vulnebilities or bugs that might occur. 

Code Snippet from Venkatesh's file scanning Algorithm
```rust
struct file {
  size: i32,
  type: str,
  requires_apv: bool
};

// Uses std::fs::File
fn scan() {
  let mut downloaded_file = File::create(file_path).unwrap();
  downloaded_file.metadata().unwrap().len();
}
```

# It's a Modern OS
The OS features it's very own Desktop Environment which has a simmilar resemblance to Apple's Mac OS.


Copyright (c) 2022-2023 Venkatesh Mishra, All rights reserved.
Copyright (c) 2022-2023 Netwrk3, Inc. All rights reserved.
