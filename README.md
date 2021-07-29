## eHills ##
Welcome to eHills, the interactive bidding game that you can play anytime! 

To maintain academic integrity, the source code is not included in this repository. However, the JAR files are available, so the project can still be run.

You can also view images of the project being run in the "Screenshots" folder.

## Goal of the game ##
The aim of the game is to place the highest bid within the time limit and successfully win the item. Multiple clients can be set up on one computer under different usernames. 

Some features include the ability to view:
  - the name, image, and description of a selected item
  - the current highest bidder on the item or the winner of the bid if applicable
  - the history of bids on a selected item
  - the history bids for that particular user themself
  - the history of bids in the entire auction

There is also a search feature that checks to see if there is an item and/or customer that matches the query. 
Whenever a user wants to complete their session, they may use the "Quit" button to do so.

Please refer to "Documentation.pdf" for further information.

## Running the project ##
To run this project, first download the files onto your PC by clicking the green "Code" button and unzipping the downloaded zip file. Then, open the Server folder, double click the Server JAR file, and wait until the server is set up with the items folder and derby.log file created. If rerunning the project, ensure the timestamp of the items folder and derby.log file match the current time. This ensures new files are created, which is necessary to run the Server again.
Afterwards, open the Client folder and double click the Client JAR file to start bidding. 

After running the project, enter a username for the Client that is opened. Then, select an item from the dropdown menu. View the remaining time at the counter on the bottom left-hand corner of the GUI. Then, view the current status of the item. If someone paid the "Buy it Now" price, you should try another item. Otherwise, meet or surpass the current bid value to place a valid bid. Continue viewing other items through the dropdown and repeat the process until time runs out or someone pays the "Buy it now" price for the selected item.

The "input" file in the Server folder holds all of the information that the game is based on. Each line represents an item in the game. The item's properties are (in order):

title, starting bid price, description, time limit to buy, buy it now price, and image of item.   

Feel free to modify any of these elements by opening the input file in Notepad if interested, but ensure that they will not cause any issues to the project i.e. make sure the image file has the same name as in the input file and that it is in the same directory. Changes will only take place once the Server is restarted i.e. closing the project and running it again.

## Closing the project ##
To close the project, use the "Quit" button on however many Client GUIs you open. Then, turn off the server by going to your Task Manager's "Details" tab and terminating any "javaw.exe" processes. The server is otherwise still running and waiting for any potential Clients to be connected to it.  
