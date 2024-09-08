# LAWxLLM_Hackathon
Event #4  - Sept 8th 2024

# AI-RE Transaction Coordinator

## Background: 

When purchasing real estate, there are multiple stakeholders involved, including a buyers agent, sellers agent, escrow officer and transaction coordinator. Prospective buyers engage a "buyers agent" to assist with locating, negotiating, and closing on a transaction. The buyers agent often hires a transaction coordinator who ensures all documents have been received and the transaction is going smoothly. 

## Problem:

A transaction coordinator is expensive, and the buyer of real estate is paying for their services indirectly. However, the transaction coordinator role is necessary as there are many documents to collect, verify and send to escrow. Many issues can arise as a result of improper documentation such as a void contract, loss of earnest money, etc. 

## Milestones:
1. Define the document types that we expect a buyer to upload. Create a jupyter project with upload functionality for these document.
2. Use llamaParse to tell if each documet type is completed. Output to the user if it is done or not
3. When a document is uploaded, prompt the user to enter (or just know?) when a document is due. Have some sort of notification functionality to prompt a user before a document is due
4. Create the same functionality for the seller side.
5. Use Llama to have a chat bot where a user can ask questions about the property or the status of the process.

## Solution:

Our proposed solutions is an interface that outlines a series of predermined steps that are necessary to close on a real estate transaction. These steps are:
- Offer Submission
- Offer Accepted
- Home Inspection & Contingencies
- Loan Approval
- Appraisal
- Final Walkthrough
- Closing Documents & Signature
- Funds Transfer
  
This interface collects relevant documentation from the buyer and seller and uses Llama to verify whether the documents are legal and complete. The solutions includes a chatbot where the buyer and seller can ask specific questions on about the transactions, including offer details, timelines, etc. 

We propose an AI solution that accepts documents from the buyer, verifies them and 
