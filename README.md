Welcome to eHills, the interactive bidding game that you can play anytime! 

To maintain academic integrity, the source code is not included in this repository. However, the JAR files are available, so the project can still be run.

To run this project, first open the Server folder, click the Server JAR file, and wait until the server is set up with the items folder and derby.log file created. 
Then, open the Client folder and click the Client JAR file to start bidding. 

After running the project, enter a username for the Client that is opened. Then, select an item from the dropdown menu. View the remaining time at the counter on the bottom left-hand corner of the GUI. Then, view the current status of the item. If someone paid the "Buy it Now" price, you should try another item. Otherwise, meet or surpass the current bid value to place a valid bid. Continue viewing other items through the dropdown and repeat the process until time runs out or someone pays the "Buy it now" price for the selected item.

To close the project, use the "Quit" button on however many Client GUIs you open. Then, turn off the server by going to your Task Manager's "Details" tab and terminating any "javaw.exe" processes. The server is otherwise still running and waiting for any potential Clients to be connected to it.  

The aim of the game is to place the highest bid within the time limit and successfully win the item. Multiple clients can be set up on one computer under different usernames. 

Some features include the ability to view:
  - the name, image, and description of a selected item
  - the current highest bidder on the item or the winner of the bid if applicable
  - the history of bids on a selected item
  - the history bids for that particular user themself
  - the history of bids in the entire auction
There is a search feature that checks to see if there is an item and/or customer that matches the query. 
Whenever a user wants to complete their session, they may use the "Quit" button to do so.

Please refer to "Documentation.pdf" for further information.
