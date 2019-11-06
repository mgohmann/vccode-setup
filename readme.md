# VS Code Setup

## Install VS Code

- [Download VS Code](https://code.visualstudio.com/)

## Install the PowerShell Extension

1. Open **VS Code**.
2. Click **View**, click **Extensions**.
3. In the** Search Extensions in Marketplace** box type "PowerShell".
4. Click **PowerShell**, click **Install**.
5. Close **VS Code**.

## Install Extensions

1. Open **VS Code**.
2. Click **Terminal**, click **New Terminal**.
3. Run the following PowerShell code in the terminal.

```PowerShell
$Extensions = @('ms-vscode.azure-account','msazurermtools.azurerm-vscode-tools','coenraads.bracket-pair-colorizer','eamodio.gitlens','davidanson.vscode-markdownlint','ed-elliott.azure-arm-template-helper')

$Extensions | foreach {code --install-extension $_}
```
  