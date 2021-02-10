## Optimize an existing website for SEO, Performance, and Accessibility
 
### I have been tasked with preforming an audit of an existing portfolio page.

The area of focus is to identify potential improvements in semantic html, keyword usage, optimization for speed and accessibility. 

Since the site owner has chosen to target local businesses in Atlanta Georgia, Local (geographic) SEO optimization is important. 

The live version of Mike's site before changes can be found <a href="https://dev-kris.github.io/OC-Optimize-Existing-Website-SEO/site-before-changes/index.html"> HERE </a>

This is the summary of the lighthouse result before any optimization.

<img src="https://github.com/Dev-kris/OC-Optimize-Existing-Website-SEO/blob/main/site-audit/audit-before-changes.png" height="200px">

It is important to note that while the site's SEO score appears high, the lighthouse report does not go beyond very basic on-page SEO rules.

It is very possible to have a 100 score on actual SEO while is poorly optimized. 

This is the full lighthouse report in PDF format before any optimization.  <a href="https://github.com/Dev-kris/OC-Optimize-Existing-Website-SEO/blob/main/site-audit/Lighthouse%20Report%20Before.pdf">:open_file_folder:</a>


This is the summary of the lighthouse result after optimization.

<img src="https://github.com/Dev-kris/OC-Optimize-Existing-Website-SEO/blob/main/site-audit/audit-after-changes.png" height="200px">

This is the full lighthouse report in PDF format after optimization. <a href="https://github.com/Dev-kris/OC-Optimize-Existing-Website-SEO/blob/main/site-audit/Lighthouse%20Report%20After.pdf">:open_file_folder:</a>

The live version of Mike's site *after* changes can be found. <a href="https://dev-kris.github.io/OC-Optimize-Existing-Website-SEO/index.html"> HERE </a>
**status: complete**

Upon auditing the original site many mistakes and Blackhat techniques were found. Notation of these can be found within the audit spreadsheet and the presentation. 

The most egregious offense was the use of hidden 1px "invisible" keywords. 

This practice is easily detectable and will result in negative ranking or outright removal from google results.

An example is provided below.

<img src="https://github.com/Dev-kris/OC-Optimize-Existing-Website-SEO/blob/main/site-audit/blackhat-example.png" height="100px">

## Best Practices
While auditing this site it was found to be using an outdated version of jQuery (2.1.0).  
It has been migrated to the current release version to address potential security vulnerabilities. Current version is (3.5.1).  
Migration was handled using JQMigrate to ensure backwards compatibility with existing scripts.  
This identified the following issues:  
<img src="https://github.com/Dev-kris/OC-Optimize-Existing-Website-SEO/blob/main/site-audit/jquery-migration-errors.png" height="200px">

These were fixed by changing the deprecated shorthand to current standards.


Site is now awaiting review and meeting with client to review suggested revisions is scheduled. 
