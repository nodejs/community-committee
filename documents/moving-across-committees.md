# Transfering a Working Group from the Node.js TSC to the Node.js Community Committee

As interested, Working Groups that are focused on serving, growing, and building the community surrounding Node.js may decide that it would like to become a part of the Node.js Community Committee. Similarly, if a Working Group under the Node.js Community Committee is focused on more technical tasks and may want to transfer over to the TSC.

This document is a guide on how to begin the transfer process from one committee to another.

## Moving from the TSC to the Community Committee
* **Step 1**: Create an issue in the [Community Committee](https://github.com/nodejs/community-committee/issues) repository asking if the Community Committee would be willing to take the Working Group in question on as a Community Committee Working Group.
  * **Step 1.1**: If there are no objections, continue on to step two.
* **Step 2**: Create an issue in the repository for the Working Group in question, proposing the move change. Given the governance model, this will likely be a vote and will need majority approval from the Working Group's members.
* **Step 3**: Once approved, you will need to create pull requests to be removed from the TSC and added to the Community Committee, and an issue tracking the change in the relevant WG repo. 
  * **Step 3.1**: Create an issue to track the changes in the Working Group's repository. There is a template to help you with this that can be found [here](./templates/tsc_to_commcomm.md).
  * **Step 3.2**: Create an issue requesting to be chartered in the [Community Committee repo](https://github.com/nodejs/community-committee/issues). Be sure to link to the issue in the WG.
  * **Step 3.3**: Create an issue requesting to be dechartered in the [TSC](https://github.com/nodejs/tsc/issues). Be sure to link to the issue in the WG.
* **Step 4**: Once dechartered by the TSC and chartered by the Community Committee, the process is complete.

## Moving from the Community Committee to the TSC
* **Step 1**: Create an issue in the [TSC](https://github.com/nodejs/tsc/issues) repository asking if the Community Committee would be willing to take the Working Group in question on as a TSC Working Group.
  * **Step 1.1**: If there are no objections, continue on to step two.
* **Step 2**: Create an issue in the repository for the Working Group in question, proposing the move change. Given the governance model, this will likely be a vote and will need majority approval from the Working Group's members.
* **Step 3**: Once approved, you will need to create pull requests to be removed from the Community Committee and added to the TSC, and an issue tracking the change in the relevant WG repo. 
  * **Step 3.1**: Create an issue to track the changes in the Working Group's repository. There is a template to help you with this that can be found [here](./templates/commcomm_to_tsc.md).
  * **Step 3.2**: Create an issue requesting to be chartered in the [TSC repo](https://github.com/nodejs/tsc/issues). Be sure to link to the issue in the WG.
  * **Step 3.3**: Create an issue requesting to be dechartered in the [TSC](https://github.com/nodejs/community-committee/issues). Be sure to link to the issue in the WG.
* **Step 4**: Once dechartered by the Community Committee and chartered by the TSC, the process is complete. 
