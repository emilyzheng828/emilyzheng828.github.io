---
layout: post
Title: My baby steps for TDD
date: 2015-11-24 12:00:00 +0000
---

# What is the purpose of the test?

Inside each test, you are generally trying to do four things:

- Set up the data needed for the test
- Perform the action that triggers the behavior being tested
- Perform one or more assertions to verify that the behavior triggered in the previous step had the expected results
- Tear down any data structures that need to be removed before the next test runs

Uncle bob describs Test Driven Development in terms of three simple rules:

- You are not allowed to write any production code unless it is to make a failing unit test pass.
- You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
- You are not allowed to write any more production code than is sufficient to pass the one failing unit test.

It might take me sometime to digest these, as so far, the TDD behaviour are pretty ...'slow no brainer' movement.....

#Vim learning today
:set paste: goes into Paste mode - bear in mind you can only escape from paste mode with Esc or C-[ 
:set nopaste: exit Paste mode - always, always exit paste mode when you're done with pasting', otherwise Vim starts to act weird.

