### Contributing to the [IATI tools](http://opendevtoolkit.net/resources/online-iati-tools.html) page 

The tools page is written in [yaml](http://yaml.org/spec/). 

To add a **new** tool to the page, please add at least the name of the tool and the URL.

For tools already mentioned - please fill in **whichever fields you can** (whether you were involved directly in creating the tool or not).

If you have a Github account, you can edit the file directly via Github [here](https://github.com/zararah/opendevtoolkit/blob/gh-pages/_data/tools.yml) just by clicking 'Edit'. 


| Property | Expected Type | Description |
| -------- | ------------- | ----------- |
| **name** * | Text | Name of tool |
| **url** * | URL | Project / tool URL |
| **aim** | Text | What is the tool's aim, or why was it created? eg. "to make it easy for people to understand where UK aid is being distributed" |
| **audience** | Text | Who are the end users/target audience of the tool? eg. "citizens in the UK" |
| **tech** | Text | Programming languages / technologies that are used within the tool, eg. "javascript, python, D3" |
| **source** | Text or URL, written out in HTML | Either text describing the data source(s) that the tool draws upon, or if a link would be useful, please write out the URL in html |
| **github** | URL | (If open source) URL of where the source code can be found, eg. https://github.com/zararah/opendevtoolkit |
| **creator** | Text | The organisation/individual/institution who developed the tool, as specific as possible |
| **wishlist** | Text | How would you (as the creator of the tool) or you (as a user of the tool) like to see the tool extended? Are there any features that you felt were missing? (Imagination recommended here!) |
| **status** | Text | Production / beta / prototype / proof of concept / other |
| **documentation** | URL | URL to any existing development documentation for the tool |

*Required fields 

This is an example, filled out for the proof of concept tool 'Organisation-ID-a-tron' - it appears [like this](http://opendevtoolkit.net/resources/online-iati-tools.html#organisation-id-a-tron) on the tools page. 

[yml]
```yaml

	 -name: Organisation-ID-a-tron
	  url: http://practicalparticipation.github.io/organisation-id-tool/
	  aim: to help publishers of data to the International Aid Transparency Initiative, and related standards, to identify the Organisation Identifier they should use, based on the draft Organisational Identifier Conventions.
	  audience: IATI publishers 
	  tech: unknown
	  source: Partial list of prefixes maintained <a href="http://docs.google.com/a/okfn.org/spreadsheet/ccc?key=0AnWngmdQt3stdFppMWdkcXJqVTRWTk9menR1N0FXNGc/">here</a>
	  github: https://github.com/practicalparticipation/organisation-id-tool/
	  creator: Tim Davies
	  wishlist: 
	  - A form for suggesting new prefixes
	  - Validation tools to check IDs - where a resolution service is available and documented in the prefix source file
	  - A tool to turn IATI IDs back into their component parts
	  - Guidance on declaring relationships between different organisational IDs
	  status: "Proof of concept, created at Developers for Development, Montreal, January 2014"
	  documentation: <a href="http://iatistandard.org/getting-started/organisation-data/organisation-identifiers/">Organisation Identifiers</a> 
```
