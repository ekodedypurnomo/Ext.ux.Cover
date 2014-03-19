Please see the wiki for documentation/references.

Latest Changes
---
- v0.2.5
    * Fixed issue with scrollable: false adding a scroll element. Changed to null to avoid issues and unnecessary dom elements.
    * Tested with ST 2.3.0 and 2.3.1

- v0.2.4
    * Fixed issue with onDrag see [issue #3](https://github.com/elmasse/Ext.ux.Cover/issues/3)
    * Tested with ST 2.2 and 2.2.1

- v0.2.3
    * Fixed small issue for ST 2.1.1
    * Tested with ST 2.1.0
    * Tested with ST 2.2.0-rc

- v0.2.2
	* Compatibility for ST 2.0.0 GA final version.
    * flat property added.
    * Fixed updating Store data, select event.
    * Fixed itemCls appeared twice per item (once for tpl wrap and once for item wrapper -This was removed-) 
    

    Known issues:
    Still not working properly on any Android device :(

- v0.2.1
	* activeItem has been deprecated for Coverflow to avoid issues with the same parameter in Card Layout. Use selectedIndex instead.

- v0.2.0 - Coverflow for Sencha Touch 2 PR2 
	* First Beta Release for Sencha Touch 2 PR2

- v 0.1 - Coverflow for Sencha Touch 1.1
	* First Beta Release for Sencha Touch 1