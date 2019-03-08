# TemplateGroups
ProcessWire module that allows limiting templates for new pages based on user groups. Requires apeisa's [UserGroup](https://github.com/apeisa/UserGroups) module.

## Status

Beta - Proof-of-Concept, use at your own risk (though this shouldn't be too high as the module saves all settings in its own database table)

## Compatibility

Tested with ProcessWire 3.0

## Usage

- Download ZIP file and extract it under site/modules in your ProcessWire installation
- In PW's backend, click on Modules -> Refresh
- Install TemplateGroups
- Edit the templates you want to limit and select the groups that should be able to use them in the "Family" tab
 
Restrictions entered here will be applied after the regular regular restrictions in the template's family settings are applied, which means you can't make an already excluded template visible in the drop-down list for new page through this method, only disallow otherwise allowed templates.

## License

Released under Mozilla Public License v2. See file LICENSE for details.
