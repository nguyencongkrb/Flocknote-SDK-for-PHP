# Flocknote-SDK-for-PHP

# Introduction

The Flocknote SDK for PHP allows easy interaction with the Flocknote API for PHP-based applications and websites.

# Usage

To use the Flocknote class in your PHP project, simply include the flocknote.php file in this repository, and create a new Flocknote instance with your app's ID and authentication key. For example:

    ```php
      include_once('flocknote.php');
      if ($flocknote = new Flocknote(MY_APP_NAME, MY_APP_KEY)) {
        // Set the username and password for this request.
        $flocknote->setUserCredentials(USERNAME, PASSWORD);
        // Get a note with ID 123.
        $note = $flocknote->getNote(123);
      }
    ```

Most API objects and methods are implemented in this class; you can read through the thorough documentation for each method in the Flocknote class by reading through flocknote.php. More examples of SDK usage can be found in Flocknote's API documentation pages.

# API Documentation

Documentation for the Flocknote API can be found on the Flocknote website: [Flocknote API Documentation](http://www.flocknote.com/help/api).
