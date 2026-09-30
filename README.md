# APS Automation API - Update Revit Titleblocks

![.NET 8](https://img.shields.io/badge/.NET-8.0-blueviolet)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🚀 Overview

**Update Revit Titleblocks** is a .NET 8 solution designed to automate the process of updating title blocks in Autodesk Revit projects.

This project was created to demonstrate APS Automation API capabilities as presented in Autodesk University 2025 session 3136, "Moving from Revit API Add-Ins to the Design Automation API: A Beginner’s Guide."  
Learn more at: [AU2025 Session 3136](https://www.autodesk.com/autodesk-university/class/Moving-from-Revit-API-Add-Ins-to-the-Design-Automation-API-A-Beginners-Guide-2025)

---

## 📦 Solution Projects

### **RevitAutomationUpdateTitleblocks**

This is a **Revit Add-in project** designed to work with the Autodesk Design Automation API. It contains the core logic for updating title blocks in Revit files and is intended to be executed in the cloud via the Design Automation service. The add-in is packaged and uploaded as a bundle for remote execution.

### **LocalDebug**

This project is designed to enable **local testing and debugging** of the `RevitAutomationUpdateTitleblocks` add-in. It provides a local harness to simulate the Design Automation environment, allowing you to run and debug the add-in directly within Visual Studio and Revit, without deploying to the cloud.

---

## 🛠️ Prerequisites

- **Windows 10/11**
- **.NET 8 SDK**  
  [Download .NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- **Visual Studio 2022** (recommended)  
  [Download Visual Studio 2022](https://visualstudio.microsoft.com/vs/)
- **Autodesk Revit 2025**
- (Optional) **Git** for source control

---

## ⚙️ Building the Solution

1. **Clone the repository:**
- git clone https://github.com/nseirs/revit-automation-update-titleblocks.git cd revit-automation-update-titleblocks

2. **Open the solution in Visual Studio 2022:**
- Double-click the `.sln` file or open it via __File > Open > Project/Solution__.

3. **Restore NuGet packages:**
- Visual Studio will prompt you, or right-click the solution and select __Restore NuGet Packages__.

4. **Build the solution:**
- Press `Ctrl+Shift+B` or select __Build > Build Solution__.

---

## 🐞 Debugging

1. **Set your startup project:**
- Right-click the desired project in Solution Explorer and select __Set as Startup Project__.

2. **Configure debugging options (if needed):**
- Go to __Project > Properties > Debug__ to set command-line arguments or environment variables.

3. **Start debugging:**
- Press `F5` or select __Debug > Start Debugging__.

---

## 📬 Using the Postman Collection

This solution includes a Postman collection and environment to help you test and interact with APS API endpoints.

### 1. Import the Postman Collection and Environment

- Open [Postman](https://www.postman.com/downloads/).
- Click **Import** in the top left.
- Select the provided `.postman_collection.json` and `.postman_environment.json` files from the repository (typically found in the `postman/` or `docs/` folder).

### 2. Configure the Environment

- In Postman, go to the **Environments** tab.
- Select the imported environment (e.g., `AU2025 - Revit Automation`).
- Update variables as needed.
- Any other variables specific to your deployment.

### 3. Run Requests

- Select the imported environment from the environment dropdown (top right).
- Open the collection and expand to see available requests.
- Click on a request, review/edit parameters if needed, and click **Send**.
- Review the response in the lower panel.

---

## 📄 License

This project is licensed under the MIT License.

---

## ✍️ Written By

- Sam Nseir ([@samnseir](https://github.com/nseirs))
- Mark Rocha ([@markrocha](https://www.linkedin.com/in/mark-rocha-p-e-s-e-ba190917/))
- Zach Smith ([@zachsmith](https://www.linkedin.com/in/smithzach75/))

---
