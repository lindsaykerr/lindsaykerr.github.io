---
title: "Python script for deleting copies of files"
active: false 
link: https://github.com/wrenzenzen/python-delete-file-duplications
year-span: "2021-2022"
tech: ["Python"]
---

The intended use for this script is under unique circumstances. When a large number of files have been copied unintentionally. The user may then wants to remove the copies whilst keeping the original files intact, they can run this script. The script does not perform any deep checks on file equality, and simply checks the file name for the common operating system prefixes and postfixes assigned to copies. It should be noted by the user that the script will also delete files that have been copied and then altered.