# ArchitecturalDebtImplications

## Project Structure

This project contains two folders named `arcan-output` and `designite-output` respectively. `arcan-output` contains the results of the projects analyzed with ArcanCLI tool while `designite-output` contains the results of the projects analyzed with Designite. 

## Project Analyzed with Arcan

This is the list of the projects analyzed with Arcan

* [Train ticket](https://github.com/FudanSELab/train-ticket)
* [Cloud shop](https://github.com/yun19830206/CloudShop-MicroService-Architecture)
* [Qbike](https://github.com/JoeCao/qbike)
* [Sitewhere](https://github.com/sitewhere/sitewhere)
* [MRPMicro](https://github.com/microsoft/PartsUnlimitedMRP)
* [Tea Store](https://github.com/DescartesResearch/TeaStore)
* [Java micro-service](https://github.com/apssouza22/java-microservice)
* [FTGO-application](https://github.com/microservices-patterns/ftgo-application)
* [Micronaut](https://github.com/asc-lab/micronaut-microservices-poc)

## Results

Folder `arcan-output` contains the files generated with the analysis of Arcan

## Instalation of Arcan

1. Once you have a copy of ArcanCLI, create an alias to the arcan.sh file: `$ alias arcan="path/to/arcan.sh"`
2. Use the following command to run the analysis: `arcan analyze -i project-source/ -p output-folder/ -o output --all -t -l JAVA --startDate 2021-03-23 --endDate 2021-03-23 output.writeProjectMetrics=true`. In the above command, replace `project-source` with the folder containing the project you want to analyze; `output-folder` with the folder where the analysis results will be stored; and the parameters `--startDate` and `--endDate` with the start and end dates of the project version you want to analyze.

## Project Analyzed with Designite

This is the list of the projects analyzed with Designite

* [MediaR](https://github.com/jbogard/MediatR)
* [Gigya](https://github.com/gigya/microdot)
* [ModernArchitectureShop](https://github.com/alugili/ModernArchitectureShop)
* [Podcast](https://github.com/microsoft/dotnet-podcasts)
* [Dotnet Istanbul](https://github.com/suadev/dotnet-istanbul-microservices-demo)
* [Enterprise planner](https://github.com/gfawcett22/EnterprisePlanner)
* [Vehicle tracking](https://github.com/mohamed-abdo/vehicle-tracking-microservices)
* [Netcore MS](https://github.com/aspnetrun/run-aspnetcore-microservices)
* [Ocelot](https://github.com/ThreeMammals/Ocelot)
* [Wetext](https://github.com/daxnet/we-text)

## Results

Folder "designite-output" contains the files generated with the analysis of Designite

## Installation of Designite

1. Download Designite from the official website: https://www.designite-tools.com/
2. Extract the downloaded file to your desired location
3. Add the Designite installation path to your system's PATH environment variable
4. Run the analysis command: `designite -i project-source/ -o output-folder/ -f XML,HTML`

Replace 'project-source' with the folder containing the project you want to analyze and 'output-folder' with the folder where the analysis results will be stored.
