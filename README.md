# Scratch Block Extension: Square Operator

## Overview

This project add a new block for calculating the square and square root of a number.



Follow  steps to create blocks:

1. **Clone Repositories:**
   - Clone the following repositories:
     - [scratch-gui](https://github.com/scratchfoundation/scratch-gui)
     - [scratch-vm](https://github.com/scratchfoundation/scratch-vm)
     - [scratch-blocks](https://github.com/scratchfoundation/scratch-blocks)

2. **Install Dependencies:**
   - Install project dependencies using the appropriate package manager (e.g., `npm install`).

3. **Link Repositories:**
   - Link `scratch-blocks` and `scratch-vm` to `scratch-gui` using `npm link`
   - and in scratch-gui use `npm link scratch-vm scratch-blocks`

4. **Create New Operator Block:**
   - Inside `scratch-blocks/blocks_vertical/operators.js`, add a new block for 'Square' and 'SquareRoot'.
   - Define the functionality of the Square block to output the square of the given number.

5. **Implement Logic in scratch-vm:**
   - Create the logic for the Square block inside a new function in `scratch-vm/src/blocks/scratch3_operators.js`.
     
6. **Implement interface in scratch-gui:**
   - Create the interface for the Square and root block inside a new function in `scratch-gui/src/lin/make-toolbox-xml`.
     
7. **Build scratch-blocks:**
   - Rebuild `scratch-blocks` by `npm run prepublish` to apply the new changes.

8. **Restart the Project:**
   - Restart the Scratch project to see the changes.
