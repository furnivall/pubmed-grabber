# pubmed-grabber
CLI tool to retrieve the full text of open access papers from PubMed Central using a DOI, written in Rust.

# PubMed-grabber

A command-line interface (CLI) tool written in Rust that retrieves the full text of open access papers from PubMed Central using a DOI.

## Installation

To install and compile the CLI tool, you'll need to have Rust installed. You can install Rust from [the official website](https://www.rust-lang.org/tools/install).

Clone this repository:

```bash
git clone https://github.com/yourusername/pubmed-central-full-text-retriever.git
```

Change to the repository directory and build the project:
```bash
cd pubmed-central-full-text-retriever
cargo build --release
```
The compiled binary will be located in the ./target/release/ directory. You can add this directory to your system's PATH or copy the binary to a directory that is already in your PATH.

## Usage
To use the CLI tool, run the following command, replacing your-doi with the DOI of the paper you want to retrieve:
pubmed-central-full-text-retriever your-doi

This will output the full text of the paper if it's available as open access on PubMed Central.

## Limitations
- This tool currently only supports open access papers. Accessing papers behind a paywall or requiring university credentials is not supported.
- The full text might be in different formats (e.g., HTML, XML, or PDF) depending on the paper. Handling and parsing these different formats is not currently implemented.

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Please feel free to open a pull request or create an issue for any bugs, feature requests, or improvements.
