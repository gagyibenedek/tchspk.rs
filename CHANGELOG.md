# Changelog

## 0.2.3
2017/02/17: CFP data updates & portal calendar fixes.

* ADDED portal `/cfp` caching & forced updates via `?update=1`
* FIXED calendar.js JSON loading

## 0.2.2
2017/02/09: Basic portal support for the TechSpeakers CFP calendar.

* ADDED `/cfp` on the portal to display upcoming CFP deadlines
* FIXED no longer swallowing CFP calendar update network & parse errors

## 0.2.1
2017/01/26: API support in the portal, integrated @Mte90's TechSpeakers Map.

* ADDED API support in the portal module
* ADDED https compatibility
* ADDED TechSpeakers data forwarding (temporary)
* ADDED TechSpeakers map visualization.
* DOCS documented new API feature
* DOCS updated example config

## 0.2.0
2017/01/26: Major update, adds auto-deploy support, breaks up experiments into their own modular components, also adds initial portal module and various fixes.

* ADDED portal module
* ADDED PM2 auto-deploy support
* ADDED `PREVIEWS` setting can now take any number of days
* FIXED moved the cfp-bot to the module format
* FIXED modules use common configuration format
* DOCS documented portal module
* DOCS updated example config

## 0.1.3
* ADDED add CFS to recognized designators in title (call for submissions)
* FIXED weekly tweet overflow detection ("& more" tag wasn't added properly)

## 0.1.2
* ADDED ability to send previews (special messages for tomorrow's content)
* ADDED `PREVIEWS` config setting
* FIXED highlights ordering
* DOCS documented new Previews feature
* DOCS updated example `config.json`

## 0.1.1
* FIXED dateskipping issue
* ADDED `DEBUG` config setting

## 0.1.0
* Initial Release
