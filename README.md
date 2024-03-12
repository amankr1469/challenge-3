# 🎮 Algorand Coding Challenge: Fix The Bug 🐞!

## 🚩 Challenge 3: My AppClient is Broken! 😭
> I want to instantiate an app client to deploy and interact with my smart contract but it's not working!!

This project includes a simple `helloWorld` smart contract written with [TEALScript](https://tealscript.netlify.app/) inside of `./contract/helloWorld.algo.ts` file. The smart contract is already compiled with artifacts generated inside of the `./contracts/artifacts` folder and the application typed client inside of `./contracts/clients/helloWorldClient.ts` file. 

The `index.ts` file in the root level is a script that deploys the `helloWorld` smart contract and calls the `helloWorld` method.

However, if you try to run the `index.ts` file after going into the `challenge` directory, opening Docker Desktop, and then running:

```bash
algokit bootstrap all
algokit localnet start
npm run start
```
it will fail.

**Find out what is wrong and fix the bug.**

> 💬 Meet other hackers working on this challenge and get help in the [AlgoKit Discord Channel](https://discord.com/channels/491256308461207573/1065320801970180168)!

## Checkpoint 1: 🧰 Prerequisites 

1. [Install AlgoKit](https://github.com/algorandfoundation/algokit-cli/tree/main?tab=readme-ov-file#install).
2. Install [Docker](https://www.docker.com/products/docker-desktop/). It is used to run a local Algorand network for development.
3. Install [Node.JS / npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) 

**Make sure to install these 3 prerequisites before continuing!**

## Checkpoint 2: 💻 Set up your development environment 

1. [Fork this repository.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
2. Clone the repository
```bash
cd [DIRECTORY_OF_YOUR_CHOICE]
git clone [FORKED_REPO_URL]
```
3. Open the cloned repository with the code editor of your choosing.

Video walkthrough of forking and cloning this repository:

https://github.com/algorand-fix-the-bug-campaign/challenge-1/assets/52557585/acde8053-a8dd-4f53-8bad-45de1068bfda

Now you are ready to fix the bug!

## Checkpoint 3: 🐞 Fix the bug 🧐

1. Open Docker Desktop and launch Algorand localnet by running `algokit localnet start` in your terminal [For more info click me!](https://github.com/algorandfoundation/algokit-cli/blob/main/docs/features/localnet.md#creating--starting-the-localnet). 
2. Go to `./contracts/helloWorld.algo.ts` to read the `helloWorld` TEALScript smart contract and understand what it does.
3. Go to `./index.ts` and read the comments on the file and fix the bug!
4. After fixing the bug run the below command inside the `challenge` directory: 
```bash
npm run start
```
If you see something like the image below, you have successfully fixed the bug! Congratulations 😆
<img width="1379" alt="image" src="https://github.com/algorand-devrel/fix-the-bug-private/assets/52557585/cadebf91-503d-46fb-a575-e6305e1719a0">

**😰 Are you struggling?**
Here is a hint for you: https://developer.algorand.org/docs/get-details/algokit/features/generate/?from_query=algokit%20utils#1-typed-clients

## Checkpoint 4: 💯 Submit your answer 

1. After fixing the bug, push your code to your forked Github repo and [make a PR to the original repo.](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork) 
2. Inside the PR include:
   1. What was the problem?
   2. How did you solve the problem?
   3. A screenshot of your terminal that shows the console.log <img width="1379" alt="image" src="https://github.com/algorand-devrel/fix-the-bug-private/assets/52557585/cadebf91-503d-46fb-a575-e6305e1719a0">

## Checkpoint 5: 🏆 Claim your certificate of completion NFT! 🎓

The Algorand Developer Relations team will review the submission and "approve" the PR by labeling it `Approved`. Once it's approved, we will share the magic link to claim your certificate of completion NFT in the comment of the PR!

> The certificate of completion NFT is a verifiable credential minted on the [GoPlausible platform](https://goplausible.com/) that follows the W3C standard for certificates and OpenBadges standard for badges. 

🎉 Congratulations on completing the challenge Algodev! Now on to the next one 💪
