
# Bash Cheatsheet
https://devhints.io/bash

### cool editing tricks
`ENV=test-env-value`
|Command|Example|Description|Value|
|--|--|--|--|
|  #value| ${ENV#test-} |remove the string after the "#"| env-value|

```bash 
${FOO%suffix} 	Remove suffix
${FOO#prefix} 	Remove prefix
${FOO%%suffix} 	Remove long suffix
${FOO##prefix} 	Remove long prefix
${FOO/from/to} 	Replace first match
${FOO//from/to} 	Replace all
${FOO/%from/to} 	Replace suffix
${FOO/#from/to} 	Replace prefix
```
