# Project templates plugin

Templates is a plugin to create and manage project template

###Features###
* Create and manage template
* Create project from template

###Installation###
Clone *projets templates plugin* into <redmine_path>/plugins

``` $ cd /<redmine_path>/plugins ```
``` $ git clone https://github.com/KernelCorp/redmine-project-templates.git ```

Run migration

``` $ cd /<redmine_path>/plugins/redmine-project-templates ```
``` $ rake redmine:plugins:migrate ```

Restart your Redmine web servers