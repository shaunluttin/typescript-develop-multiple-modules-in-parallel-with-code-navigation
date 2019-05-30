This repository demostrates TypeScript Project References with code navigation.

### Usage

Clone the repository and enter its directory. Then link the two packages:

    cd package01
    npm link

    cd ../package02
    npm link @shaunluttin/package01

After linking the two packages, open the repository in VS Code.

Code navigation will work when we press `F12` on `package01` from within `package02/index.ts`.
