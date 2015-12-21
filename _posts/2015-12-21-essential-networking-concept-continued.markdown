---
layout: post
date: 2015-12-21 12:00:00 +0000
title: "Service Models"
---
Imagine you are posting a Christmas card from UK to China, it might be posted by air, by ship or by train. How the card gets China does now matter. So far, remmember this. 

With a connnection-oriented servie, a connection must be established before data can be transferred.Communication consists of three phases:
1. Connection set up
2. Data transfer
3. Connection release

For connection setup, either layer n requests that a connection be set up to some destination address, or layer n-1 informs layer n that some layer n process in some other node is requesting a connection.

For connection release, either layer n requests that a connection be released, or layer n-1 informs layer n that the layer n process in the other node (or some other condition) requires release of the connetion.

#Vim learning today :Sex
In normal mode type :Sex to split the current window and open Explore above it. Or :Sex! to split vertically. If the current window has no file, the current directory is opened (as shown by :pwd). (Also see :Hex, :Vex, and :Tex commands for slight variations).
Navigate to a file name using hjkl, or arrow keys.

Press R to rename a file.

A prompt is shown that the selected file will be moved (renamed), and the original full path for the destination is shown. Change that path as wanted and press Enter to move the file, or Esc to cancel.
