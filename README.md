# LangChain4j Report
--- 

LangChain4j 1.0.0-beta1

## System Report

| Operating System    | JDK       | Maven | Architecture | Full Build | Date  | Notes |
|---------------------|-----------|-------|--------------|------------|-------|-------|
| CentOS Stream 9     | Eclispe Adoptium 17  | 3.9.6 | PPC64LE      |   | Feb 5, 2025 | |
| MacOS 15.3          | Eclispe Adoptium 17 | 3.9.9 | AArch64      |  | Feb 5, 2025 | |
| Ubuntu 22.04 LTS    | Eclispe Adoptium 17  | 3.9.5 | x64      |  | Feb 5, 2025 | |
| Ubuntu 24.04 LTS    | Eclispe Adoptium 17  | 3.9.8 | x64      |  | Feb 5, 2025 | |


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
