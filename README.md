# COMPUTER NETWORKS ASSIGNMENT 1 (B20EE030)
## How to run the code?
1. Delete all the content of `config.txt` file.
2. Delete the content of `outputpeer.txt` and `outputseed.txt` for better understanding of the output. (Not mendetory step)
3. Run the given code snippet in terminal to activate a seed node
```
python seed.py
```
4. Give a **unique port no.** for the seed address as the input.
5. Run the given snippet (point 3) in multiple instances of terminal to get multiple seed nodes. **Make sure to provide unique port numbers for every instance.**
6. Run the given code snippet in terminal to activate a peer node
```
python peer.py
```
7. Give a **unique port no.** for the peer address as the input.
8. Run the given snippet (point 6) in multiple instances of terminal to get multiple peer nodes. **Make sure to provide unique port numbers for every instance.**
9. Now the network is up and running. You can check the `terminal` OR the `outputpeer.txt` and `outputseed.txt` files for the logs.

## Extra Features implemented
### 1. Automatic updation of `config.txt`.
- As new seeds are created they automatically get added to the config file. No need to input the seed address manually. 


### 2. Implemented continues user interaction with both seeds and peers.
- When the user runs `seed.py` file, they will be asked to get the current status and address of the connected peer nodes.
- When the user runs `peer.py` file, they will be asked to get the current status and address of the connected peer nodes as well as the seed nodes.
