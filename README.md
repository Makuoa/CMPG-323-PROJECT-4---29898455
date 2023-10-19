# CMPG-323-PROJECT-4---29898455
# Read me file
# # Overview

This project focuses on automating user acceptance testing (UAT) for a web application using Robotic Process Automation (RPA) with UiPath. UAT is a critical step in the software development process to ensure that the application performs as expected. In this project, we will automate the testing of a web application to validate that input data results in the desired output.

Web Application: The web application to be tested is hosted at https://cmpg323-ecopowerlogistics.azurewebsites.net/.

#  Who Can Use This Automation?

# # This automation project can be used by:

Developers: To streamline the UAT process and ensure that the web application works as expected before deployment.
Testers: To automate repetitive testing tasks and reduce manual testing efforts.



# # Benefits of Automation

    Efficiency: Automation reduces the time and effort required for testing, making the UAT process faster and more efficient.

    Accuracy: Automation eliminates the possibility of human errors during repetitive testing, ensuring accurate results.

    Consistency: Automated tests provide consistent and repeatable results, allowing for more reliable testing.

    Resource Optimization: Automation frees up human resources to focus on more complex and creative tasks, while repetitive testing is handled by the robot.

# # Testing process

    Read the Input Data: Data is read from an Excel file into a data table in UiPath. This data includes the input data records that will be used to test the web application.

    UI Automation: The UiPath robot interacts with the web application's user interface, mimicking the actions that a human tester would perform. This involves the following steps for each record:

    a. Navigate to the Web Application: The robot opens a web browser and navigates to the URL of the web application.

    b. Insert Data: The robot enters the data from the input record into the appropriate fields on the web application. This could include filling out forms or interacting with UI elements.

    c. Submit Data: Once the data is filled out, the robot clicks the 'submit' button or performs the action required to create a new record on the web application.

    d. View Created Record: After creating a new record, the robot navigates to the URL where the newly created record can be viewed. This step ensures that the record was successfully added to the application.

    Record Results: Based on the outcome of the previous steps, the robot updates the data table record to reflect whether the test was successful or not. If the new record was created as expected, the data table is updated to indicate a successful test. If the record was not created or had errors, the data table is updated to show a failed test.

    Update Excel Spreadsheet: The robot updates the Excel spreadsheet with the testing results. The 'Test Results' column in the Excel file is updated with either 'TRUE' (for a successful test) or 'FALSE' (for a failed test).

The UiPath robot repeats these steps for each input data record, automating the entire UAT process. This approach ensures that the web application is thoroughly tested for each set of input data without the need for manual testing.

The key to successful testing in this project is the accurate automation of user interactions with the web application. UiPath provides the tools and capabilities to simulate user actions, which allows for efficient and reliable testing.

## References

- - > Simplilearn (2023) A step-by-step guide to uipath installation, Simplilearn.com. Available at: https://www.simplilearn.com/tutorials/rpa-tutorial/uipath-installation (Accessed: 12 October 2023).
    
- - > McKenzie, C. (2020) How to create a UiPath orchestrator process to run robots, TheServerSide. Available at: https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/How-create-a-UiPath-Orchestrator-process-to-run-your-RPA-robots (Accessed: 12 October 2023).

- - > How can we read the data from Excel to Ui Path? (no date) Quora. Available at: https://www.quora.com/How-can-we-read-the-data-from-Excel-to-UI-Path (Accessed: 12 October 2023).
    
- - > How can we read the data from Excel to Ui Path? (no date) Quora. Available at: https://www.quora.com/How-can-we-read-the-data-from-Excel-to-UI-Path (Accessed: 12 October 2023).
    
- - > Masuth (2018) Row by row iteration, UiPath Community Forum. Available at: https://forum.uipath.com/t/row-by-row-iteration/56946 (Accessed: 17 October 2023).
    
- - > (No date) What is a data table? (with types, example and tips) - indeed. Available at: https://www.indeed.com/career-advice/career-development/what-is-a-data-table (Accessed: 16 September 2023).
    
- - > Callahan, E. and Mitchell, P. (no date) Fixing access annoyances, O’Reilly Online Learning. Available at: https://www.oreilly.com/library/view/fixing-access-annoyances/059600852X/ch04.html (Accessed: 19 September 2023).
    
- - > Bourgeois, D. and Bourgeois, D.T. (2014) Chapter 4: Data and databases, Information Systems for Business and Beyond. Available at: https://pressbooks.pub/bus206/chapter/chapter-4-data-and-databases/ (Accessed: 14 October 2023).
    
- - > Boboc, M. (no date) Excel automation tutorial - datatables automation, UiPath. Available at: https://www.uipath.com/learning/video-tutorials/excel-datatables-automation (Accessed: 16 October 2023).
- - > Boboc, M. (no date a) Excel automation tutorial - datatables automation, UiPath. Available at: https://www.uipath.com/learning/video-tutorials/excel-datatables-automation (Accessed: 16 October 2023).
    
- - > (No date a) Docs.uipath.com. Available at: https://docs.uipath.com/studio/standalone/2023.4/user-guide/ui-automation (Accessed: 18 October 2023).

- - > https://www.uipath.com/rpa/robotic-process-automation
    
- - > https://www.britannica.com/technology/automation

- - > Uipath Studio: Your first process automation (2020) YouTube. Available at: https://www.youtube.com/watch?v=OyQAhrcBr9U (Accessed: 11 October 2023).
    
 - - > Automation (2023) Encyclopædia Britannica. Available at: https://www.britannica.com/technology/automation (Accessed: 17 October 2023). 
  

