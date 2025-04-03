Cybersecurity Awareness ChatBot

Overview

The Cybersecurity Awareness ChatBot is a simple console-based chatbot designed to educate users about cybersecurity. The chatbot provides guidance on password safety, phishing, and safe browsing. It responds to user queries based on predefined responses and keyword recognition.

Features

Interactive chatbot experience with a typing effect.

Educates users on cybersecurity best practices.

Recognizes keywords related to cybersecurity topics.

Displays an ASCII logo representation of an image.

Plays an audio greeting message when launched.

Prerequisites

Before running the application, ensure you have:

Visual Studio (2019 or later) installed.

.NET Core SDK (if not included with Visual Studio).

Windows OS (for sound playback functionality).

Installation and Setup

Clone or Download the Repository

git clone https://github.com/your-repository/chatbot.git

Or manually download and extract the ZIP file.

Open the Project in Visual Studio

Launch Visual Studio.

Click "Open a project or solution".

Navigate to the project folder and open the .sln file.

Restore Dependencies

Open the Package Manager Console in Visual Studio.

Run the command:

dotnet restore

Ensure Required Files Are Present

Place the logo.jpeg file in the project's root directory.

Ensure the Greeting Message.wav file is also in the root directory.

Running the Application

Build the Project

Click on Build > Build Solution or press Ctrl + Shift + B.

Run the ChatBot

Press F5 to run in debug mode.

Or click on Start Without Debugging (Ctrl + F5).

Usage Instructions

When the chatbot starts, it will ask for your name.

After entering your name, it will greet you and prompt you for questions.

You can ask about cybersecurity topics like:

"What is phishing?"

"How do I create a strong password?"

"Tell me about safe browsing."

To exit the chatbot, type exit.

Troubleshooting

Chatbot does not display properly?

Ensure your console supports colored output.

Audio not playing?

Verify the Greeting Message.wav file is present in the root directory.

Logo not displaying?

Ensure logo.jpeg exists and is accessible in the correct directory.

Future Improvements

Add more advanced AI-based responses.

Implement GUI for better user experience.

Expand cybersecurity topics covered.
