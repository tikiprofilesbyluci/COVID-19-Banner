# COVID-19 Banner
COVID-19 Banner profile for Tiki creates and assigns a custom module to your site featuring customizable "banner" where you can put information related to your community or business affected by the Wuhan (China) originated coronavirus 2020 pandemic.

## Download
Get the released package from the Releases on Github (https://github.com/tikiprofilesbyluci/COVID-19-Banner).

## Installation
How to install (aka apply) the profile?  
You will need an access to your command line on your localhost or via SSH on the server where your Tiki is installed. Unpack the profile somewhere, e.g. you can create new dir named `profiles` in your Tiki site root folder. Then run the following command in your terminal to apply it:  
`php console.php profile:apply profiles/ProfileName`

Alternatively (if you prefer GUI or have no command line access) you can install it directly from your Tiki by adding the profiles.luciash.eu profiles repository to your Profiles control panel.

## Screenshots
![Screenshot](./COVID-19%20Banner.png)

## Usage
This profile creates a custom module with a "COVID-19 Banner" in it.
The module will be assigned to the _bottom_ modules zone but the banner will appear on fixed position on the top of your website.

After applying the profile the module is visible only to _Admins_. When you are done with the customization and the module content is ready to be published just edit the assigned module in the bottom zone and remove the Admins group from the groups field.

You can put whatever you want instead of the "__Due to the COVID-19 pandemic situation, we are ...__" text.

When you click the Close button, a cookie named `covid19-banner` is stored in your browser and the module content will be hidden.

## Uninstall
Just unassign and delete the module on the _Settings → Modules (tiki-admin_modules.php)_ page.
