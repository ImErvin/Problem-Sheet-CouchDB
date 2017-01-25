# **Problem-Sheet:** _CouchDB_

Answers to the **CouchDB Problem Sheet** for _Data Representation and Querying_.

**Steps**
 * **Step 1:** Run the database, and test your ability to perform a HTTP request on it. Do this by
performing a GET request on it for the root resource.
 * **Step 2:** Create a new database called emails.
 * **Step 3:** Create a file called email1.json containing JSON representing an email. (You can make
up your own properties and values.) Use curl to add email1.json as a document to the
emails database.
 * **Step 4:** Add a second, different document to the database. (Again make up your own properties
and values.)
 * **Step 5:** Retrieve all of the document ids from the database. Then do the same again, except
this time including all of the document contents. Finally, individually retrieve each of
the documents you created above.
 * **Step 6:** Update the first document you created in the database, changing some of the properties
in the document. Check to make sure your document has been updated, by retrieving
it.
 * **Step 7:** Delete the first document you added to the database, and then retrieve all documents
to confirm it has been deleted.
 * **Step 8:** Write a simple CouchApp where users can store JSON objects entered into a textarea
in a web page.
