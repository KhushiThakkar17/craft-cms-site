# Craft CMS Site — ORA Research Office

Explored and configured Craft CMS architecture to model a university 
research administration office website, simulating the structure of 
the UMD VPR/ORA web presence.

## Content Structure Built
- 4 custom entry types: News, Staff, Resources, Announcements
- 3 sections: Singles (Homepage), Channels (News), Structures (Resources)
- 10+ custom fields: Plain Text, Rich Text, Assets, Date, Dropdown
- Custom field layouts per entry type

## Templates
- _layout.twig — Base layout with header, nav, footer
- index.twig — Homepage template
- news/_entry.twig — Individual news entry
- staff/index.twig — Staff directory listing
- resources/index.twig — Resources listing page
- contact.twig — Contact page

## Key Concepts
- Twig templating with template inheritance using extends and blocks
- Dynamic content rendering from Craft CMS entries
- URL routing via section settings
- Plugin configuration and system settings management
- CMS lifecycle: installation, content modeling, template development

## Tech Stack
Craft CMS, PHP, Twig, MySQL, XAMPP

## How It Relates to ORA GA Role
The VPR and ORA websites run on Craft CMS. This project directly 
prepares me for maintaining content, updating templates, and managing 
the CMS lifecycle as a Graduate Assistant.
