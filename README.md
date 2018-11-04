# Humanoid Analysis
---
## Project info
---
	- Start date: Nov 4,2018
	- End date: TBD
	- Project type: Support document
	- Initial input: NULL
	- Language: English
	- Dependencies: NULL
	- Estimated completion: 0%

## PIC list:

	1. SilverBam

## Project format

### Rule
	1. Each document store in an .node file (Well just for design purpose, it just normal text, NotePad++ or Sublime will do the job)
	2. Each .node only answer one question from its parent .node
	3. Each .node contain its ID code, parents .node ID
	4. Each .node must contain list of question for analyzing and list of incurred question
	5. .node ID is a format of 32 bits hexcemal numbers which show its deepth, and its index number
	6. .node ID deepth mask 0xFC00 (1111 1100 0000 0000), its ID index mash is 0x03FF(0000 0011 111 111)
	7. Example: Root .node is 0x0000(0000 0000 0000 0000) which mean Root .node have deepth of 0 and index of 0
	8. Example 2: example.node ID is 0x4001 (0100 0000 0000 0001) which mean example.node have deepth of 2 and index of 1
	9. .node file name must consist of .node ID and .node short summary

###### _Addition Rule may be added as the project go on_


## Task list

	 1. Project initial
		- [x] Git repository
		- [x] README.md
	 2. Analysis
		- [x] Root Analysis
	 3. Layer 1
	 	- [ ] Question 0x000->1
	 	