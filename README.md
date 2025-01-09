# LangChain4j Report
--- 

LangChain4j 0.36.2

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9     | Eclispe Adoptium 17  | 3.9.6 | PPC64LE      |  Success | Jan 9, 2025 | |
| MacOS 15.2          | Eclispe Adoptium 17 | 3.9.9 | AArch64      | Success | Jan 9, 2025 | |
| Ubuntu 22.04 LTS    | Eclispe Adoptium 17  | 3.9.5 | x64      | Success | Jan 9, 2025 | |
| Ubuntu 24.04 LTS    | Eclispe Adoptium 17  | 3.9.8 | x64      | Success | Jan 9, 2025 | |
| Windows 11 Pro      | Azul Zulu 17  | 3.8.5 | x64      | Failure  | Jan 9, 2025 | Could not resolve dependencies on dev.langchain4j.langchain4j-open-api jar 0.37.0-SNAPSHOT|
| Windows 11       | MS OpenJDK 17  | 3.9.8 | AArch64      | Failure | Jan 9, 2025 | Could not resolve dependencies on dev.langchain4j.langchain4j-open-api jar 0.37.0-SNAPSHOT|


## Errata


Fast build to assure compilation. 
```
mvn clean install -Dmaven.test.skip=true
```

On Windows:
```
mvn clean install "-Dmaven.test.skip=true"
```

## How to use this repo

Main branch is latest release of LangChain4j

A branch is created for each release to record lab results.
