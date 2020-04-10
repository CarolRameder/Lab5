# Lab5

Document Management System

Write an application that can manage a catalog of documents. An entry in this catalog might be an article, a book, etc.
A document may be located using a path in the local file system or a link to an external URL. Each document has a unique ID, a name and may have additional tags, which are pairs name-value. Example of tags may be title, author, year, publishingDate, etc.

The task:

Create an object-oriented model of the problem. You should have at least the following classes: Catalog, Document. Consider creating a class responsible with external operations regarding a catalog.

Implement the following methods:

save: saves the catalog to an external file, using object serialization;

load: loads the catalog from an external file.

view: opens a document using the native operating system application (see the Desktop class);
