first thing I did was the HTML file.
I started by adding a div so all the work will be there and also because i only have one div without any header or footer.
then I added the form, so all the data be stored there and send directly to the database.

I created a database called task, it has 7 column all of type int: from 1 to 6 it belongs to the machines and the degree the user choice, 
the last column belongs to the status. it will store two values only, either 0 or 1.
it will store 0 when the user clicks on SAVE only.
and it will store 1 if he clicks on the PLAY button.

then I made a css file which will contain the styling of my page, and I link the html page with the css styling page.
and I applied everything i need and added the photo.

after that I made a php page and link the user Interface with the database I created.
and also, I make sure that the data being inserted to the database, otherwise it will show a message that the data could not added to the database.

NOTES:
===================================================
you have to download XAMPP.
then you have to put this file in 'htdocs' inside the XAMPP folders.
how to run? go to the browser , then type 'localhost' followed by the port number , ex:1234 ,then the folder name 
Example:localhost:1234/Tasks/

now you can rotate the engines and send the data to the database.

also note that in the video i recorded, i show the user interface and i SAVE the data and show it to you after it is being 
inserted to the database and it has '0' in it's status.
And when i try again with diffrent data and push the PLAY buttoun, data will be stored also and the status will contain '1'.
