# Homestead Craft

Homestead Craft is Homesteads CLI tool that has a number of helpful commands to help you while you are building your application.
Using the commands in Craft will ensure you are creating items that conform to the Homestead standards.

# Commands

## Creating A New Project

<div id="termynal" class="use-termynal" data-termynal>
    <span data-ty="input">craft project init</span>
    <span data-ty="input">app_name[]: input app name here</span>
    <span data-ty="input">app_domain[localhost]: setup app domain - localhost for local dev</span>
    <span data-ty="input">app_port[8000]: input app port here</span>

</div>


## Creating and Mangaging Modules

Creating a new module is as simple as running the following command:

<div id="termynal" class="use-termynal" data-termynal>
    <span data-ty="input">craft module create module-name</span>
</div>

Depending on if you choose web or api this will create a module in the web or api folder respectively.