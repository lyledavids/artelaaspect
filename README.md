# Sunny
## Use Case Summary
**Sunny** is a platform that connects freelancers and clients in a decentralized and transparent manner. The DApp is built on a blockchain, ensuring security, transparency, and trust in transactions. It leverages smart contracts for automated payments and dispute resolution, reducing the need for intermediaries.

## Team Members and Roles
Team Member 1: [Lyle Davids - Smart Contract Dev]

## Problem Addressed
Sunny changes the freelancing landscape by addressing critical issues prevalent in traditional platforms. Leveraging blockchain technology, this decentralized application (DApp) introduces a trust-infused environment with transparent identity verification, reputation tracking, and a secure escrow system powered by smart contracts. Clients benefit from a reliable payment mechanism, facilitated by cryptocurrency transactions, minimizing international transaction challenges and reducing fees. The platform ensures the authenticity of freelancers through decentralized identity verification and establishes a reputation system supported by oracles for skill verification. By immutably recording work history on the blockchain, the DApp offers freelancers an unalterable portfolio, fostering trust among clients. Decentralized governance empowers users to actively participate in decision-making, promoting a sense of community ownership. With collaborative tools, decentralized file sharing, and a robust dispute resolution system, Sunny transforms freelancing into a secure, transparent, and community-driven ecosystem.


## Project Design

### Key Features

#### 1. Decentralized Identity Verification

Utilize blockchain for identity verification, ensuring that freelancers and clients have authenticated profiles. This enhances trust within the platform.

  

#### 2. Smart Contract Escrow System:

Implement smart contracts to create an escrow system for payments. Funds are held in escrow until the project is completed, providing security for both freelancers and clients.

  

#### 3. Decentralized Reputation System:
Develop a reputation system using blockchain to track and verify the performance and reliability of freelancers. This helps clients make informed decisions when selecting freelancers for their projects.





#### 4. Tokenized Payments:
Integrate a cryptocurrency payment system for transactions within the platform. This can be paid with stablecoins and Artela's future native token



#### 5. Skill Verification Through Oracles:
Use decentralized oracles to verify freelancers' skills and achievements, providing clients with additional confidence in the capabilities of the freelancers they choose.



#### 6. Decentralized Governance:

Allow platform users to participate in the decision-making process through decentralized governance mechanisms. Users can propose and vote on changes to the platform, making it a community-driven ecosystem.


#### 7. Immutable Work History:
Store work history and project details on the blockchain, creating an immutable record of completed projects. This can serve as a portfolio for freelancers and a reference for clients.



#### 8. Integrated Collaboration Tools:
Include collaboration tools such as decentralized file sharing, messaging, and project management to facilitate smooth communication and project workflow.

#### 9. Decentralized Dispute Resolution:
Implement a decentralized dispute resolution mechanism using smart contracts and community voting. This ensures fair and unbiased resolution in case of conflicts between freelancers and clients.





## Value to the Artela Ecosystem
Sunny enriches the Artela ecosystem by demonstrating the practical utility of Artela's blockchain technology in the freelancing industry. Through the innovative use of smart contracts for secure escrow systems, transparent identity verification, and decentralized governance, the DApp showcases Artela's robust capabilities. The platform's commitment to storing immutable work history and reputation data on the Artela blockchain underscores the network's capacity for transparent and tamper-proof record-keeping. By promoting cross-platform compatibility and fostering community-driven decision-making, Sunny contributes to Artela's growing reputation as a leading platform for decentralized applications, encouraging wider adoption and showcasing Artela's role in revolutionizing various industries.


## Contract Overview
Smart contract functions in AssemblyScript to  handle various aspects of the freelancing platform. Here's an overview of how some key functions might work

1. **User Registration and Identity Verification:**
   ```typescript
   export function registerUser(userAddress: string, username: string, identityHash: string): void {
       // Implementation to store user details on the blockchain
   }
   ```

2. **Project Creation:**
   ```typescript
   export function createProject(projectId: i32, client: string, projectDetails: string, budget: i32): void {
       // Implementation to create a new project and initiate escrow
   }
   ```

3. **Freelancer Proposal Submission:**
   ```typescript
   export function submitProposal(projectId: i32, freelancer: string, proposalDetails: string): void {
       // Implementation to record freelancer proposals on the blockchain
   }
   ```

4. **Smart Contract Escrow System:**
   ```typescript
   export function depositEscrow(projectId: i32): void {
       // Implementation to handle the deposit of funds into escrow
   }
   ```

5. **Skill Verification through Oracles:**
   ```typescript
   export function verifySkill(freelancer: string, skill: string, skillScore: i32): void {
       // Implementation to leverage oracles for skill verification
   }
   ```

6. **Decentralized Governance:**
   ```typescript
   export function proposeChange(changeDetails: string): void {
       // Implementation to allow users to propose changes to the platform
   }
   ```

7. **Payment Release and Dispute Resolution:**
   ```typescript
   export function releasePayment(projectId: i32): void {
       // Implementation to release funds and handle dispute resolution
   }
   ```

8. **Immutable Work History:**
   ```typescript
   export function recordWorkHistory(freelancer: string, projectId: i32, projectDetails: string, successful: bool): void {
       // Implementation to record completed projects on Artela
   }
   ```
