# business-rules-kata
This Repository will encompass my proposed solution for the Code Kata Business Rules, this Code Kata can be found in the Readme file below along with my solution.

## The Problem
You can find the link to the problem [here](http://codekata.com/kata/kata16-business-rules/).
In summary, the main issue with the problem that has been identified in the original post is the company in question has continued to add to it's products requirements without streamlining its processes.

## The Solution
The solution for this issue involves the following:
1. A product centric configuration that outlines the requirements for that product, ie receiptSentTo: accountOwner, deliverySlipSentTo: accountOwner, royaltyTeam
2. Action based functions that are called based on the product at submission time, ie sendReceipt, sendDeliverySlip, upgradeSubscription
3. Create all basic functionality that allows the system to perform basic tasks that are required during submission and transactions, ie sendEmail, updateAccount, requireUserConfirmation

For reference you can take a look at the Product-List xml file in the working directory of this repository as an example of how the system would be setup.

## What's Next?
I will be looking to build out some basic functionality to show the use cases for how Product Types would be processed at submission.
