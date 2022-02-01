# Installation
___

There are a couple of ways to install Homestead. 

The easiest way is to pip install it globally.  

This will allow you to easily create a project anywhere you want 


<div id="termynal" class="use-termynal" data-termynal>
    <span data-ty="input">pip install homestead</span>
</div>

# Creating a New Project
___

After you have installed Homestead , you can create a new project. 

We will Homestead's cli `craft`.

Create a new directory where you want to create your project and cd into it.
Then run `craft project init`

<div id="termynal" class="use-termynal" data-termynal>
    <span data-ty="input">mkdir ~/projects/homestead_project</span>
    <span data-ty="input">cd ~/projects/homestead_project</span>
    <span data-ty="input">craft project init</span>
</div>

# Setting Up Your Virtual Environment
___

Homestead comes with both a pyproject.toml and a requirements.txt file. 

This will allow you to create a virtual environment anywhere you want. 

## Creating a Virtual Environment With Poetry
___

Make sure you are in the root directory of your project.

<div id="termynal" class="use-termynal" data-termynal>
    <span data-ty="input">poetry install</span>
</div>

<br />

This will create a poetry virtual environment. 

You can see the virtual environment information by running `poetry env info`.

<div id="termynal" class="use-termynal" data-termynal>
    <span data-ty="input">poetry env info</span>

    <span data=ty>Virtualenv</span>
    <span data-ty><span style="color: green;">Python:</span>: 3.10</span>     
    <span data-ty><span style="color: green;">Implementation:</span>: CPython</span>
    <span data-ty><span style="color: green;">Path:</span>: ~/Library/Caches/pypoetry/virtualenvs/homestead-RYWbZD7k-py3.10</span>  
    <span data-ty><span style="color: green;">Valid:</span>: True </span>

</div>
