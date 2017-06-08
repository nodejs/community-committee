# Transfering a Working Group from the Node.js TSC to the Node.js Community Committee

As interested, Working Groups that are focused on serving, growing, and building the community surrounding Node.js may decide that it would like to become a part of the Node.js Community Committee. Similarly, if a Working Group under the Node.js Community Committee is focused on more technical tasks and may want to transfer over to the TSC.

This document is a guide on how to begin the transfer process from one committee to another.

## The Committee Transferring Checklist
Here's a checklist for you to get started with transferring committees. This list is meant to help a Working Group make sure everything that _needs_ to be complete to effectively transfer committees actually _is_ complete. 

- [] Ensure the Working Group is in alignment on moving from the current committee to the new committee
- [] Have the currrent committee vote to decharter
- [] Have the new committee vote (and approve) a new charter
- [] Mark that the Working Group has been dechartered in the Working Groups documentation for the current committee
- [] Submit a PR to the new committee adding the Working Group to the Working Groups documentation for the new committee

## In depth: A guide to moving from one commmitte
While the process of moving from one top level committee to another is likely going to be one of the smoother parts of this process, we've documented it in case you want some help with going through the process of this transition.

### Moving from the TSC to the Community Committee
* **Step 1**: Create an issue in the repository for the Working Group in question, proposing the move. Given the governance model, this will likely be a vote and will need majority approval from the Working Group's members.
* **Step 2**: Create an issue in the [Community Committee](https://github.com/nodejs/community-committee/issues) repository asking if the Community Committee would be willing to take the Working Group in question on as a Community Committee Working Group.
  * **Step 2.1**: If there _are no objections_, continue on to step two.
  * **Step 2.2**: If there _are objections_ by the committee, the group requesting the transfer can either address feedback and try again or remain under their current committee.
* **Step 3**: Once approved by both the WG and the Community Committee, you will need to create two pull requests: one pull request to be dechartered by the TSC and one pull request to be chartered by the Community Committee.
* **Step 4**: Once dechartered by the TSC and chartered by the Community Committee, the process is complete.

### Moving from the Community Committee to the TSC
* **Step 1**: Create an issue in the repository for the Working Group in question, proposing the move. Given the governance model, this will likely be a vote and will need majority approval from the Working Group's members.
* **Step 2**: Create an issue in the [TSC](https://github.com/nodejs/TSC/issues) repository asking if the TSC would be willing to take the Working Group in question on as a TSC Working Group.
  * **Step 2.1**: If there _are no objections_, continue on to step two.
  * **Step 2.2**: If there _are objections_ by the committee, the group requesting the transfer can either address feedback and try again or remain under their current committee.
* **Step 3**: Once approved by both the WG and the TSC, you will need to create two pull requests: one pull request to be dechartered by the Community Committee and one pull request to be chartered by the TSC.
* **Step 4**: Once dechartered by the Community Committee and chartered by the TSC, the process is complete.
