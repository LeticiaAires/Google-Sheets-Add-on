# Background

As part of my quest for self improvement both in tech knowledge acquisition and personal project execution, I aim to develop a chrome extension that will create a more user-friendly interface for managing and visualizing data from my finance Google Sheets document.

# Reasoning Behind Software Decisions

While I can implement this project thorugh other tech solutions, such as a Google Apps Script or a Standalone Web Application, I would most importantly like to develop my front-end skills in JS, HMTML, CSS and Google Cloud, however, there are also some other motivations for this choice.

1. Customized User Experience (UX):
  A Chrome extension allows you to build a completely custom interface that sits on top of or alongside Google Sheets. This interface can be designed to be more intuitive, with better forms for data entry, dynamic charts, and other interactive elements.
2. Direct Interaction with Google Sheets:
  Through the Google Sheets API, your extension can read and write data to the sheet, ensuring that any changes made through the custom interface are reflected in the actual sheet. This provides seamless integration with the existing data structure.
3. Cross-Platform Accessibility:
  Since the extension runs in Chrome, it will work on any platform where Chrome is available, allowing you to access and interact with your data from any device with the browser.
4. Control Over Data Presentation:
  You can implement custom data visualizations, like charts and graphs, that are tailored to your specific needs and update in real time as you modify the data.
5. Integration with Other Google Services:
  You can integrate other Google services like Google Drive, Google Calendar, or even Gmail to provide a more comprehensive budgeting and financial management tool.

# Challenges

As there are benefits to the selected software solution, there are also aspects that require sensitive handling in order for it to work out.

1. Complexity
   Building a fully functional extension that manages authentication, interacts with the Google Sheets API, and provides a rich UX could be complex and time-consuming, especially if you are not familiar with Chrome extension development.
2. Maintenance:
   You’ll need to maintain the extension, handling updates and changes in both Google’s APIs and Chrome’s extension framework. This can add ongoing work, especially as web technologies evolve.
4. Security Considerations:
   Handling OAuth for accessing Google Sheets securely requires careful consideration of how you manage tokens and user permissions. Chrome extensions have strict content security policies that you must adhere to, adding another layer of complexity.

   ## Now here we go!
