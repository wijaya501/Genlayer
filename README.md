# GenLayer AI-Powered Voting

An Intelligent Contract project on the GenLayer Testnet

## 📝 Description
This is a simple voting contract built using GenLayer's `.gen` language. 
The key feature is AI verification to check if the vote reason is relevant and not spam.

## ✨ Key Features
- Create new votes with a topic
- Vote with a required reason
- AI checks the reason automatically
- Get real-time voting results

## 🚀 How to Use
1. Deploy `Voting.gen` to GenLayer Testnet
2. Call `createVote("Your Topic")`
3. Call `vote(voteId, true, "Your reason")`
4. Check results with `getResults(voteId)`

## 🛠️ Tech Stack
- Language: GenLayer `.gen`
- Network: GenLayer Testnet

Built for GenLayer Builder Program 2026
