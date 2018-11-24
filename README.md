# Tool-chain for Software Visualization
아래과 같은 도구로 Tool-chain을 구성한다.
![toolchain](./toolchain.png)
* Source Navigator
소스 네비게이터는 파서로써 소스 코드를 스캔하고 기존 C, C++, Java, Tcl, FORTRAN, COBOL 등과 같은 프로그램에서 정보를 추출하여 dbdump를 생성한다.

* SQLite
소스 네이게이터를 통해 분석된 데이터를 데이터베이스화 하는데 SQLite를 사용한다.

* Graphviz (Dot Script)
소프트웨어 품질 지표나 출력하고 싶은 정보를 Dot 스크립트를 작성하여 그래프화 시켜주는 도구이다.

## Getting Started

자바, C/C++과 같은 프로그램을 소스 네비게이터를 통해 구문 분석을 하고, 그 결과로 나온 SNDB 파일을 SQLite 데이터베이스에 저장하고 필요한 정보를 추출하여 Dot 스크립트를 통해 그래프로 소프트웨어 가시화를 한다. 

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
