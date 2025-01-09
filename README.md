# LangChain4j Report
--- 

LangChain4j 0.36.2

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9     | Eclispe Adoptium 17  | 3.9.6 | PPC64LE      |  Success |  | |
| MacOS 15.2          | Eclispe Adoptium 17 | 3.9.9 | AArch64      | Success |  | |
| Ubuntu 22.04 LTS    | Eclispe Adoptium 17  | 3.9.5 | x64      | Success |  | |
| Ubuntu 24.04 LTS    | Eclispe Adoptium 17  | 3.9.8 | x64      | Success | | |
| Windows 11 Pro      | Azul Zulu 17  | 3.8.5 | x64      |  |  | |
| Windows 11       | MS OpenJDK 17  | 3.9.8 | AArch64      |  |  | |


## Errata


Fast build to assure compilation. 
```
mvn clean install -Dmaven.test.skip=true
```

## How to use this repo

Main branch is latest release of LangChain4j

A branch is created for each release to record lab results.
