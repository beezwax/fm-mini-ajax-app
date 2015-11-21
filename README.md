## fm-mini-ajax-app

This is a collection of simple web apps using a basic AJAX JavaScript &amp; handler to connect to the XML interface provided by FileMaker Server.

They are not intended as complete solutions, but could be helpful if you need to orient yourself to working with this type of code. It has also proven useful for debugging issues with FileMaker's XML interface.

Uses vkBeautify.js for the two "rawxml" examples, which can be found at https://github.com/vkiryukhin/vkBeautify

## Installation

To use these files you'd typically install them into one of the directories at:

### Mac OS
/Libary/FileMaker Server/HTTPServer/htdocs
/Libary/FileMaker Server/HTTPServer/htdocs/httpsRoot

### Windows
C:\Program Files\FileMaker\FileMaker Server\HTTPServer\Conf

## Files

### rawxml_1.html 

This file simply dumps the raw XML result for all records in the sample file using the Projects layout. Uses the vkbeautify.js file to format the XML result.

### rawxml_2.html

Building on the previous file, this adds fields where the file name and the layout can be specified.

### html_table.html

Typically, the XML result will need to processed in some way. Here we format some of the fields
as an HTML table write out the results.

