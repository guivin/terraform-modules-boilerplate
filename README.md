# terraform-modules-boilerplate

This project is a boilerplate for creating new Terraform modules. 

When you create a new module you repeat the same actions. 

The goal here is to have a ready-made template to create robust and quality Terraform modules.

## Usage

Install Python requirements to use this template:

```
$ python -m pip install -r requirements.txt --user
```

Create a new terraform module from the template:

```
$ cookiecutter https://github.com/guivin/terraform-modules-boilerplate
```

You need to specify the following information:

* author_name: The name of the author
* author_url: The url to your Github account
* licence: The licence you want to use (default APL2)
* licence_url: The URL to your licence
* module_name: The name of your module
* provider The Terraform provider this module focuses on
