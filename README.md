# 🗳 Nirvachak -- Blockchain Voting System

Nirvachak is a **Blockchain-based voting system built using Java and
Swing GUI**.\
The project demonstrates how blockchain technology can be used to ensure
**secure, transparent, and tamper-proof digital voting**.

Each vote is stored as a block in the blockchain using **SHA-256
hashing**, ensuring that the vote records cannot be modified once added.



## 🚀 Features

-   Secure voting using **Blockchain structure**
-   **SHA-256 hashing** for block security
-   Prevents **double voting** using voter ID validation
-   **Live vote counting** during the election
-   **Blockchain visualization** showing each block's details
-   **Automatic winner calculation**
-   Election results saved to a **timestamped file**
-   Simple and interactive **Java Swing GUI**



## 🧠 How the System Works

1.  The system starts with a **Genesis Block** in the blockchain.
2.  Each vote creates a **new block** containing:
    -   Voter ID
    -   Selected Candidate
    -   Previous Block Hash
    -   Current Block Hash
3.  The block hash is generated using **SHA-256 encryption**.
4.  The hash links blocks together, forming a **secure blockchain**.
5.  Double voting is prevented using a **HashSet of voter IDs**.
6.  At the end of the election:
    -   Winner is calculated
    -   Results are saved to a file.



## 🧱 Blockchain Structure

Each block contains:

Voter ID\
Vote (Candidate Name)\
Previous Hash\
Current Hash

Hash formula:

SHA-256(voterId + vote + previousHash)

This ensures the integrity of the blockchain.



## 🖥️ Technologies Used

-   Java
-   Java Swing (GUI)
-   Blockchain Concept
-   SHA-256 Hashing
-   File Handling



## 📊 Candidates in Demo

-   Alice\
-   Bob\
-   Charlie



## 🔒 Security Features

-   12-digit Voter ID validation
-   Double voting prevention
-   Immutable blockchain structure
-   Secure hashing using SHA-256



## 📂 Output

When the election ends, results are saved in a file like:

election_results_YYYY-MM-DD_HH-MM-SS.txt

Example:

Election Results\
Total Votes Cast: 1\
Winner: Alice (1 votes)

Vote Distribution:\
Alice: 1\
Bob: 0\
Charlie: 0



## ▶️ How to Run

1.  Clone the repository

git clone
https://github.com/yourusername/nirvachak-blockchain-voting.git

2.  Open the project in an IDE

Recommended: - IntelliJ IDEA - Eclipse - NetBeans

3.  Run

Run the file:

Nirvachak.java

The GUI application will start.



## 🎯 Project Purpose

This project demonstrates:

-   Implementation of **Blockchain in Java**
-   Building a **secure digital voting system**
-   Creating **desktop GUI applications using Java Swing**


## 📜 License

This project is created for **educational and demonstration purposes**.



## 👨‍💻 Author

Blockchain Voting System using Java Swing.
