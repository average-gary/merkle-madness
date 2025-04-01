# March Madness Merkle Tree

An interactive visualization of a March Madness bracket using Merkle trees. Each team's progression through the tournament is tracked using cryptographic hashes, creating a verifiable chain of winners.

## Features

- Interactive March Madness bracket visualization
- Real-time Merkle tree hash calculations
- Color-coded team progression
- Random winner selection
- Visual path highlighting

## How to Use

1. Click on any team to select them as the winner of their match
2. Winners automatically propagate up the bracket
3. Each team's hash is derived from their name and previous matches
4. The Merkle root at the top represents the complete tournament state

## Technical Details

- Built with vanilla JavaScript
- Uses CryptoJS for SHA-256 hashing
- Responsive design that works on various screen sizes
- No external dependencies beyond CryptoJS

## Live Demo

Visit the [GitHub Pages site](https://average-gary.github.io/merkle-madness) to try it out!