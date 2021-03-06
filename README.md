Scholarly Archive Template
================================

This site template displays all of the documents in an edition and allows readers to compare different versions of the documents.

This template is written for the Jekyll framework. You can learn more about using Jekyll at: <a href="http://jekyllrb.com/" target="_blank">jekyllrb.com</a>.

To begin building your own custom template, we recommend that you fork this project on Github. This will give you a starting point you can then modify.


Juxta Editions Specific Tags
------------------------

Presently, there is only one tag introduced by Juxta Editions:


\{% edition \<key\> %\} - Adds data from your edition into your website. Current values for key are "title" and "description".


Differences from Jekyll
------------------------

The following directories and files are either ignored or used for a specific purpose by Juxta Editions:

_layouts : These are layouts which encompass content pages. comparison.html and document.html are used to layout out the comparison and document display pages that are generated by Juxta Editions. Use can modify these layouts to adjust the look and feel of these pages.

_plugins: Juxta Editions does not allow external plugins, so any plugins add in this folder are ignored when publishing the site. We supply a je_mimic.rb file here that responds with placeholder data to any tags supported by Juxta Editions.

documents : Anything placed in this directory will be ignored when the site in published. It is just for documents created using Juxta Editions.

_data : This directory also contains mock data that helps when viewing the template outside of the Juxta Editions environment.

_config.yml : All Juxta Editions sites have a preset configuration. This file is ignored when the site is published.
