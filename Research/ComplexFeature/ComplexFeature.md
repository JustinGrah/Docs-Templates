# FEATURE NAME - Research notes
![AuthorBadge][badge-author]
![OSRelease][badge-osrelease-22h2]
![PrivacyTag][badge-privacy-general]
![LevelTag][badge-level-400]

## Code references
* [Referenced Sample Repo 1](https://github.com) -> Communications with SDK 1
* [Referenced Sample Repo 2](https://github.com) -> Translation layer with SDK 2
* [Referenced Sample Repo 3](https://github.com) -> Translation into OS Layer using SDK 3
* [Referenced Sample Repo 4](https://github.com) -> Overall Service build

## Dependencies
Communication is using all SDK's mentioned [here](#code-references).  
However main communication is done using [SDK 2](https://github.com)

## Documents and Whitepapers
* [General Document](https://www.microsoft.com/en-us/microsoft-365/word)
* [Architecture overview 1](https://www.microsoft.com/en-us/microsoft-365/word)
* [Architecture overview 2](https://www.microsoft.com/en-us/microsoft-365/word)
* [Dependencie overview](https://www.microsoft.com/en-us/microsoft-365/word)

## Diagrams and Flowcharts
### Flowchart of SDK 1
![Sample picture of a flowchart]()

### Flowchart of SDK 2
![Sample picture of a flowchart]()

### Flowchart of SDK 3
![Sample picture of a flowchart]()

---
## Commands / Outputs

### controller.exe -?
**Description**: Used to generate a help message forthe tool
```
Sample Output:

controller.exe -?
> This is a sample "?" output for this non-exisiting controller.exe!
> please treat this as a sample output from a command
```
**Notes**: This could be anything that would be worth pointing out

### controller.exe show alphabet count
**Description**: Used to list the alphabet
```
Sample Output:

controller.exe show alphabet count
> 27
```
**Notes**: This could be anything that would be worth pointing out

---
## Scenarios
Any scenario that would be worth pointing out

### Invalid output
When using `controller.exe show alphabet count` it does not account for special letters like `ü,ä,ö,ß`  
You would have to change the lanugage settings using `controller.exe change alphabet lang=german`


## Troubleshooting and Commands

### Reset output
Clear any stored alphabet settings.
```
controller.exe reset alphabet -f -a
> Alphabet settings have been reset.

controller.exe show alphabet count
> No alphabet found!

controller.exe change alphabet lang=german
> Ok

controller.exe show alphabet status
> Lang: German
> Chars: 27
> Includes special chars: true
```
**Note**: Handle with care! You might loose your default language

<!-- ===========[PAGE END]=========== --->
<!-- 
====
Badge Assets 
====
-->

<!-- Author Badge -->
[badge-author]: https://img.shields.io/badge/Author-YOURNAMEHERE-brightgreen?style=flat-square&logo=microsoft

<!-- OS Release Tags -->
[badge-osrelease-22h2]: https://img.shields.io/badge/OS%20Release-22H2-brightgreen?style=flat-square&logo=microsoftazure


[badge-osrelease-21h2]: https://img.shields.io/badge/OS%20Release-21H2-yellow?style=flat-square&logo=microsoftazure


[badge-osrelease-21h1]: https://img.shields.io/badge/OS%20Release-21H1-red?style=flat-square&logo=microsoftazure


<!-- Privacy Tags -->
[badge-privacy-general]: https://img.shields.io/badge/Privacy%20Tag-General-brightgreen?style=flat-square

[badge-privacy-nda]: https://img.shields.io/badge/Privacy%20Tag-NDA%20Only-yellow?style=flat-square

[badge-privacy-internal]: https://img.shields.io/badge/Privacy%20Tag-Internal%20Only-red?style=flat-square

<!-- Level Tags -->
[badge-level-100]: https://img.shields.io/badge/Level-100%20Foundational-blue?style=flat-square

[badge-level-200]: https://img.shields.io/badge/Level-200%20Specialist-orange?style=flat-square

[badge-level-300]: https://img.shields.io/badge/Level-300%20Advanced-red?style=flat-square

[badge-level-400]: https://img.shields.io/badge/Level-400%20Expert-lightgrey?style=flat-square

<!-- 
====
Images 
====
-->