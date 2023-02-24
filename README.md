Accent Design .NET Web Developer Technical Test
===============================================

Thanks for your interest in the role of C#.NET developer at Accent Creative Digital Solutions. We are looking for an experienced full stack developer with skills in C#.NET with Entity Framework, SQL Server, JavaScript, API development and with good communication skills, to join our established team developing websites, web-based software systems and mobile apps. Successful candidates will join the team as remote workers. We are a small team, so you will be be a big part of it. Your voice will be heard and you will be expected to take on jobs outside of your comfort zone.

If you think you are up for it, then we would like you to spend 2-3 hours having a go at our little technical test, which consists of two parts - a coding test and a few technical questions.

## Coding Test

We would like you to create a web application using C#.NET that queries an API and displays the information received. 

One of Accent's major clients manages property 'For Sale' boards for estate agents across the UK. For this test, we have made an API available at http://boarderectors-api.accentstaging.co.uk/ that you will use to get information about properties managed by a specified estate agent, including the address of each property, the type of board at the property and the board's current status. We'd like you to use the PropertiesByCustomer endpoint that is documented at http://boarderectors-api.accentstaging.co.uk/swagger.

As an example, http://boarderectors-api.accentstaging.co.uk/agents/ACC001/properties returns a list of properties managed by Accent Estate Agents, who have the customer code 'ACC001', including current board types and statuses.

The task is to build upon the provided MVC application to add functionality that accepts customer code as a parameter, and does the following:

* Displays the following information about each property managed by the customer, by querying our API:
  * Property Address
  * Erected Board Type
  * Total Fee Charged
* Apply a levy to the fee charged for certain properties
  * For properties which have an erected board type of "sold", a levy of 7.5% must be applied to the total fee charged before it is displayed
  * For those with "sale agreed", a 4% levy should be applied
* Shows "grand total" of the fees charged for the properties

Feel free to spend as much or as little time on the exercise as you like as long as the following requirements have been met.

Your code should compile and run in one step.
Feel free to use whatever libraries / packages you like.
You should include tests for the most criticial code
Please avoid including artefacts from your local build (such as NuGet packages or the bin folder(s)) in your final ZIP file


## Technical Questions

Please answer the following questions in a markdown file.

1. How long did you spend on the coding test? What would you add to your solution if you had more time? 
2. What is the most useful feature that was recently added to .NET? Please include a snippet of code that shows how you've used it.
3. How would you track down a performance issue in production? Have you ever had to do this?


Please email your code to jobs@accentdesign.co.uk or upload it to DropBox or Google Drive (or similar) and send us a link.

Thanks for your time & we look forward to hearing from you!
