Municipal Services Application – README

Introduction
The Municipal Services Application is a user-friendly platform designed for citizens to report issues within their municipality, submit feedback on services, and track the status of their service requests. It aims to streamline communication between residents and municipal authorities, ensuring that problems are reported and resolved efficiently.

Features
Report Issues: Allows users to report issues (e.g., sanitation, roads, utilities) and submit relevant media.
Feedback System: Users can submit feedback and rate services to help municipalities improve.
  
System Requirements
Operating System: Windows 7 or higher
Framework: .NET Framework 4.7.2 or higher
IDE: Visual Studio 2019 or higher

Additional Libraries: 
  - Windows Forms for GUI
  - System.Drawing for media attachments
  - Entity Framework (optional, if using database features)

Setup Instructions
1. Clone the Repository
Clone the project from the repository to your local machine using Git:

2. Open the Project in Visual Studio
1. Launch Visual Studio.
2. From the menu, click on File > Open > Project/Solution.
3. Browse to the folder where the project is cloned and select the `.sln` file (e.g., `MunicipalServicesApp.sln`).

3. Restore Dependencies
In Visual Studio, ensure that all NuGet packages and dependencies are restored:
- Go to Tools > NuGet Package Manager > Manage NuGet Packages for Solution.
- Click Restore to fetch all necessary dependencies.

4. Build the Project
To compile the source code:
1. From the Solution Explorer, right-click on the project solution and select Build Solution.
2. The build output will appear in the Output window at the bottom of Visual Studio. Ensure that the build is successful.

5. Run the Application
To run the project:
1. Click on the Start button in Visual Studio or press `F5`.
2. The application window will open, and you will be able to interact with the software.


Usage Instructions
1. Report Issues
Location: Enter the location where the issue was observed.
Category: Select the appropriate issue category (e.g., Sanitation, Roads, Utilities).
Description: Provide a detailed description of the issue.
Attach Media: Optionally, click the "Attach Media" button to upload any relevant photos or videos.
Submit: Click the "Submit" button to report the issue to the municipality.

2. Submit Feedback
Feedback: Type your feedback in the text box provided.
Rating: Select a rating from 1 to 5 (1 being the lowest, 5 being the highest).
Submit: Click the "Submit" button to send your feedback and rating.

3. Navigating the App
Back to Main Menu: Use the "Back to Main Menu" button to return to the main interface.

 

Troubleshooting
Build Errors: Ensure that all dependencies are restored correctly via NuGet. If the build fails, check for any missing libraries or framework mismatches.
UI Not Displaying Correctly: Ensure that your system meets the minimum display resolution requirements (1280x720 or higher).
Unable to Submit Reports: Verify internet connectivity and check whether the necessary back-end services (if integrated) are operational.

Contact
For further assistance or inquiries, please contact:
Developer: Muhammad Ameen
Email: ST10062640@vcconnect.edu.za
