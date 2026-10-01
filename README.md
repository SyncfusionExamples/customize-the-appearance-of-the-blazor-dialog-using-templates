# Customize the Appearance of the Blazor Dialog Using Templates

## Overview

This sample demonstrates how to customize the appearance of a Syncfusion [Blazor Dialog](https://www.syncfusion.com/blazor-components/blazor-modal-dialog) Blazor WebAssembly application by using dialog templates. The implementation focuses on replacing the default dialog presentation with custom content and layout through template-based configuration while retaining the built-in dialog behavior provided by Syncfusion components. This approach enables developers to create branded modal interfaces, improve user experience, and present application-specific content in a structured and visually appealing manner. The sample serves as a practical reference for implementing customized dialog headers, content sections, and styling in real-world Blazor applications.

## Key Features

- Uses the `SfDialog` component to display a modal dialog with custom dimensions through the `Height="35%"` and `Width="435px"` properties.
- Configures the dialog within a specific container using the `Target="#target"` property.
- Enables end-user dialog dismissal through the `ShowCloseIcon="true"` property.
- Customizes the dialog header using the `DialogTemplates.Header` template.
- Displays a user avatar image in the dialog header using a custom CSS-based avatar implementation.
- Renders a personalized header layout containing profile information and custom branding elements.
- Customizes the main dialog body using the `DialogTemplates.Content` template.
- Displays a chat-style message layout within the dialog content area.
- Uses the `DialogTemplates.FooterTemplate` template to create a custom messaging interface.
- Integrates the `SfTextBox` component with `InputType.Text` and placeholder text for message input.
- Integrates the `SfButton` component with `CssClass="e-primary"` to provide a styled send action button.
- Applies custom CSS styles to modify the dialog header background, content area, footer layout, and message appearance.
- Customizes dialog close icon styling and interaction states including hover, focus, and active behaviors.
- Implements responsive layout styling for the footer input area and action button arrangement.
- Demonstrates avatar-enhanced conversational dialog designs suitable for chat, messaging, and communication scenarios.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `CustomDialogAppearance.sln` solution file.
3. Restore the NuGet packages.
4. Ensure the startup project is configured correctly.
5. Build the solution.
6. Press `Ctrl+F5` to run the application.

**Visual Studio Code**

1. Open the repository folder.
2. Navigate to the project root directory.

```bash
dotnet restore
dotnet run
```

3. Open the local URL displayed in the application output window after startup.

## Project Structure

- `Client/Pages/Index.razor` - Main sample page demonstrating a customized `SfDialog` using `DialogTemplates`, including custom header, content, footer, `SfTextBox`, and `SfButton` integration.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Documentation: https://blazor.syncfusion.com/documentation/dialog/template

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications