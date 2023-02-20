# consume_nytimes_api_in_rust
A simple project to learn how to integrate data from a third party api in a Rust project. 
The api used here is NewYork Times API.
Libraries used are: 
- Tokio: for async call
- Reqwest: as an HTTP client
- Serde: to serialize and deserialize api data into a usable format
- Futures: just like `Promise` in JavaScript, future is used to access async data when ready

## How to use
- Install rust on your machine
- Clone/for this repo
- Run: `cargo run <search query> <api key>

## To generate an api key
Register on [NewYork Times Website](https://developer.nytimes.com/get-started)
