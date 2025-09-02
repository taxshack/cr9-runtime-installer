# 📦 CR9 Runtime Installer for Visual Studio .NET 2003 (.NET 1.1)

This installer provides the essential Crystal Reports 9.x components required for applications built with Visual Studio .NET 2003 using the .NET 1.1 framework.

## ✅ Intended Use

This package is designed for environments where:
- Crystal Reports 9 was originally used for report design  
- Applications were built using **Visual Studio .NET 2003** 
- The goal is to restore runtime functionality on modern Windows systems (Win10/Win11)

> **Note:** This package targets the Crystal Reports runtime embedded with Visual Studio .NET 2003.  
> It has not been tested against the full standalone Crystal Reports 9 installation, though it may still work in those environments depending on how reports were authored and deployed.

> **Compatibility:** To the best of our knowledge, this installer does not conflict with other installed versions of Crystal Reports.  
> It is scoped narrowly to the CR9 runtime and .NET 1.1 assemblies used by VS.NET 2003 applications.

## 🔧 What This Installer Does

- Registers required Crystal Reports COM components  
- Installs key Crystal .NET assemblies to the Global Assembly Cache (GAC)  
- Applies registry patches to ensure licensing and runtime compatibility  

## 🚫 What It Does *Not* Do

- Install full Crystal Reports design-time tools  
- Support newer versions of .NET or Crystal Reports  
- Modify unrelated system components  

## 🧪 Tested Environments

- Clean installations of Windows 10 and Windows 11  
- Visual Studio .NET 2003 targeting .NET Framework 1.1  
- Applications written in **VB.NET 2003** using embedded Crystal Reports 9 runtime

## ⚠️ Disclaimer

Use at your discretion. This tool is provided as-is, with the intent to preserve legacy functionality — not to modernize or replace it.

## Stewardship & Support

This project is part of a broader effort to preserve legacy tools and community infrastructure at Art Works in Richmond, VA. If this work has helped you or if you believe in sustaining affordable art spaces and technical knowledge, consider sponsoring or donating via Venmo (@TaxShack).
