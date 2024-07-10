# **Notes**

This project was creted using **Blazor Web App template .NET 8.0**
- Interactive mode: **Auto (Server and WebAssembly)**
- Interactivity location: **Per page/component**
- CSS Library: **MudBlazor**
- 
## Issues

### The menu toggle does not work
The application main layout (**MainLayout.razor**) is set up using the **MudLayout** component from MudBlazor. Inside the **MudLayout**, there are **MudAppBar**, **MudDrawer**, and **MudMainContent** components.

The expected behavior is that when the menu icon (**MudIconButton**) is clicked, the menu (**MudDrawer**) should hide or show based on the state of the **drawerOpen** variable. However, this is not working.
