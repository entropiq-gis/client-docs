# Install

## Purpose
Install the client on a Windows machine and complete basic configuration for typical use cases.

## Prerequisites
- Admin permissions required: Yes
- Dependencies: None

## Install Steps (GUI)
1. Run the EntropiQ MSI. (e.g., EntropiQ_RNG_Provider_[version].msi)
2. Follow the prompts in the installation wizard.
3. Set the Connection Mode to API
4. Enter the path to the Entropiq API server
5. Enable "Set as Default Provider"
6. Click Next
7. Enter your API key
8. Follow the prompts to complete the installation

## Silent Install
1. Open the BAT file (e.g., INSTALL_[version].bat)
2. Paste your API Key to the set value for the AGENT_API_KEY value
3. Save your changes and close the file
4. Execute the batch script as an adminstrator

## Verify Installation
1. Open the Windodws Services Manager (services.msc)
2. Find the service names starting with "EntropiQ"
3. Verify they are running and set to Automatic
