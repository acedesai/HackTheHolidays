# HackTheHolidays
This repository is for Ace Desai contribution to the HackTheHolidays Blockchain Hackathon.

Vote Chain 

Overview: 
Large section of demographic today do not trust their government.This makes an election a very crucial aspect in a modern democracy. The issue with the current US election system is that it can be manipulated and hence is not reliable upto the large extent. Hence cryptographic techniques are employed to ensure the security of voting systems in order to increase its wide adoption. However, in such electronic voting systems, the public bulletin board that is hosted by the third party for publishing and auditing the voting results should be trusted by all participants. Recently, a number of digital solutions have been proposed to address this issue. However, these systems are impractical to use due to the limitations on the voter and candidate numbers supported, and their security techniques which are highly dependent on client-server architecture. To deal with all these issues, we propose practical platform-independent secure and distributed voting system which is developed on top the blockchain architecture. The proposed system hopes to wipe out the part of trust from an election to make it more secure and transparent. Undeniable nature is characteristically given by the fundamental blockchain design, and cryptographic methods like CSPRNG, salt hashing, proof of work are employed to enhance data security measures. There are many substantial social benefits to using the system as well such an easier and quicker voting process which will lead to higher voter turnout. We might definitely see a future where our country has implemented a system similar to ours. 


Technology-Stack:

    Front-End Development: HTML,CSS,Bootstrap,Vanilla JS,Jquery
    Data-Processing and Blockchain Development: Python 3.6.5
    Back-End Development: Django-Python Framework
    Database management: DB SQLite

Voter Authentication :

    The voter authentication is carried out in two steps and it is implemented using NCDMV API services.
    A voter has to provide his Thumb impression ID and NC DMV ID to the system which will serve as an input to Aadhaar API.
    Aadhaar API will provide the result as a basic detail of the voter if he/her has been successfully authenticated.

Vote Casting and Blockchain REST API Development:

    Here system will create a unique voter ID for the voter.
    Again the voter will cast a vote for any one of the candidate.
    After vote casting there are six different steps are carried out for which we have designed a special REST API:
        Transaction Verification
        Proof of Work Algorithm
        Block creation and Serialization
        Block Broadcasting and validation
        Consensus Algorithm
        Byzantine Fault Tolerance

Peer to Peer (Distributed) Network Design:

    A peer to peer distributed network on which the blockchain architecture works.
    A Web Socket request API for broadcasting the all the requests into P2P network.
    Handling concurrency by using a mutex lock mechanism.

Database Management:

    A relational DB SQLite is used as a database for the project.
    Many cryptographic and encryption algorithms are used to store the data securely in the database (SHA-256, CSPRNG, salt-hashing, etc).
    Complete normalization is also achieved in different relations of the database.

Admin Section:

    This panel is only reserved for the governing body of an election.
    Every admin is assigned a unique Election Commission ID for authentication.
    Result analysis of election is carried out in this section.

Architectural Control flow of the System


The operational flow of the System

Steps to run the application:

    Clone this repository.
    Change this to working directory.
    Hit command: "docker-compose up --build"
    Go to http://localhost:5000/auth/ in your browser.



