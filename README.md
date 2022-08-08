# _Project Name_

#### By _Zachary Waggoner_

#### _Description_

## Table of Contents

[Technologies Used](#technologies-used)  
[Description](#description)  
[Setup/Installation Requirements](#setup-and-installation-requirements)  
[Known Bugs](#known-bugs)  
[License](#License)

## Technologies Used

* _C#_
* _.NET_
* _HTML_
* _CSS_
* _SQL Workbench_
* _Entity Framework_
* _MVC_

---
## Description

_This is an MVC application that was built using C#. The purpose of this application is to allow the user to identify the best restaurants by their cuisine. When the application runs, the user can add a cuisine type. After the type is inputted using the "add" button, users can then add specific restaurants to that specific cuisine. The restaurant details support a name and description. Once the restaurant is added, it will appear under that specific cuisine list._

---
## Setup and Installation Requirements

<details>
<summary><strong>Initial Setup</strong></summary>  

1. Copy the git repository url: https://github.com/CyndaZ42/RecipeBox  
2. Open a shell program and navigate to your desktop.
3. Clone the repository for this project using the `git clone` command and including the copied URL.
4. While still in the shell program, navigate to the root directory of the newly created file named `RecipeBox.Solution`.
5. From the root directory, navigate to the `RecipeBox` directory.
6. Move onto SQL Workbench instructions below to re-create database necessary to run this project.
</details>

<details>
<summary><strong>SQL Workbench Configuration</strong></summary>

1. Create an `appsetting.json` file in the `RecipeBox` directory of the project*  
   <pre>RecipeBox.Solution
   └── RecipeBox
    └── <strong>appsetting.json</strong></pre>
2. Insert the following code:
  <pre>{
    "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=project_name;uid=root;pwd=[YOUR-PASSWORD-HERE];"
    }
  }</pre>
  <small>  *note: you must include your password in the code block section labeled YOUR-PASSWORD-HERE".</small>

3. Once `appsettings.json` file has been created, navigate back to SQL Workbench.
</details>

<details>
<summary><strong>To Run</strong></summary>

1. Navigate to:  
   <pre>RecipeBox.Solution
   └── <strong>RecipeBox</strong></pre>

2. Run `$ dotnet restore` in the console.  
3. Run `$ dotnet database update` in the console.  
4. Run `$ dotnet run` in the console
</details><br>

This program was built using *`Microsoft .NET SDK 5.0.401`*, and may not be compatible with other versions. Your milage may vary.

## Known Bugs

* Any known bugs

## License

_Feel free to reach out via [Github](https://github.com/CyndaZ42) to provide feedback on this project or to view my other projects._

[Copyright](/LICENSE) © 2022 Zachary Waggoner
