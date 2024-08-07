# TalkJS and Blazor example

This is an example project for TalkJS's tutorial on [how to integrate TalkJS with a Blazor app](update link).

This example demonstrates how to integrate TalkJS with a Blazor web application . There is one project present inside the repo:

- The `Blazor Web App` Interactive Server project which uses TalkJS's [JavaScript SDK](https://talkjs.com/docs/Getting_Started/JavaScript_SDK) to create a one on one chat.

## Prerequisites

To run this tutorial, you will need:

- A [TalkJS account](https://talkjs.com/dashboard/login)
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/community/) IDE with the `ASP.NET and Web Development` workload and `.NET 8 runtime` in Individual accounts tab selected while installing Visual Studio in Visual Studion installer.

## How to run the tutorial

1. Clone or download the project.
1. From the `blazor_talkjs` directory:
   1. Open the `blazor_talkjs.sln` file.
   -This will open the project in Visual Studio
   1. In the `app.razor` file:
   1. Replace `<APP_ID>` with the value found in the **Settings** tab of your [TalkJS dashboard](https://talkjs.com/dashboard/login). 
   1. Click the green run button at top-center of visual studio to run the project. Your project should be render on the browser.
