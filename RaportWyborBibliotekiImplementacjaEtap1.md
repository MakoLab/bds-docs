# Raport - wybór biblioteki dla realizacji implementacji 


## C&#35;

### Komponent: dotNetRDF

#### Krótki opis

dotNetRDF is a powerful and flexible API for working with RDF and SPARQL in .Net environments [dotNetRDF](http://dotnetrdf.org/) 

dotNetRDF is a powerful and flexible API for working with RDF and SPARQL in .Net environments, for 
details and documentation on the project please see our website at dotnetrdf.org

To get started with using dotNetRDF you may want to check out the following resources:

 - **User Guide** - Series of articles detailing how to use various features of the library
 - **Developer Guide** - Some advanced documentation
 - **MSDN Style API** - MSDN style documentation for the entire API

#### License

dotNetRDF is licensed under the MIT License, see the LICENSE.txt file in this repository

* technologia **C#**
* funkcja **triplestore API**

#### Namiary

* Link do opisu biblioteki: [dotNetRDF](http://www.dotnetrdf.org/)
* Link do kodu: [GitHub](https://github.com/dotnetrdf/dotnetrdf)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *4*
* Możliwość równomiernego rozłożenia prac *3*
* Licencja MIT
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *społeczny, ilość aktywnych developerów: 10*
* Ocena kodu przez społeczność
  * ilość gwiazdek - 40
  * ilość forków - 8,
  * ilość osób śledzących - 12
  * ilość otwartych problemów - 60
  * aktywność projektu


### Komponent: Nethereum

#### Krótki opis

Bringing the love of Ethereum to .Net

Nethereum is the .Net integration library for Ethereum, it allows you to interact with Ethereum clients like geth, eth or parity using RPC.
The library has very similar functionality as the Javascript Etherum Web3 RPC Client Library.
All the JSON RPC/IPC methods are implemented as they appear in new versions of the clients.
The geth client is the one that is closely supported and tested, including its management extensions for admin, personal, debugging, miner.
Interaction with contracts has been simplified for deployment, function calling, transaction and event filtering and decoding of topics.
The library has been tested in all the platforms .Net Core, Mono, Linux, iOS, Android, Raspberry PI, Xbox and of course Windows

* technologia **C#**
* funkcja **ethereum API**

#### Namiary

* Link do opisu biblioteki: [Nethereum](http://nethereum.com/)
* Link do kodu: [GitHub](https://github.com/Nethereum/Nethereum)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *3*
* Możliwość równomiernego rozłożenia prac *3*
* Licencja open source
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *społeczny, ilość aktywnych developerów: 9*
* Ocena kodu przez społeczność
  * ilość gwiazdek - 181
  * ilość forków - 89,
  * ilość osób śledzących - 47
  * ilość otwartych problemów - 28
  * aktywność projektu


### Komponent: CSharp2nem

#### Krótki opis

The CSharp2nem Api wrapper library is designed to simplify development on and use of the nem blockchain. CSharp2nem flexibly supports mainnet, testnet and mijin.

* technologia **C#**
* Funkcja **Nem BlockChain API**

#### Namiary

* Link do kodu: [GitHub](https://github.com/NemProject/csharp2nem)
* Link do NuGet: [CSharp2nem](https://www.nuget.org/packages/CSharp2nem/)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *2*
* Możliwość równomiernego rozłożenia prac *3*
* Licencja *MIT*
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *[NEM Project](http://nem.io) (firma), ilość aktywnych developerów: 2*
* Ocena kodu przez społeczność
    * ilość gwiazdek - 2
    * ilość forków - 0
    * ilość osób śledzących - 6
    * ilość otwartych problemów - 0
    * aktywność projektu - 74 commity, 3 branche, 2 kontrybutorów, ostatni commit: < 1 miesiąc temu

#### Dodatkowe informacje

1. Artykuł dot. porównania Ethereum vs NEM: [link](https://blog.nem.io/ethereum-versus-nem-the-obvious-choice/)
2. Porównanie Ethereum vs NEM - reddit: [Ethereum vs NEM](https://www.reddit.com/r/ethereum/comments/6c9cf6/ethereum_vs_nem/)
3. Landstead - rejestr ziem i własności: [Landstead - Land and property registry](http://landstead.atraurablockchain.com/) - rozwiązanie bazujące na NEM BlockChain
4. Wpis o Mijin - Permissioned BlockChain Platform opartej o NEM: [link](https://blog.nem.io/mijin-a-permissioned-blockchain-platform-plans-to-reduce-the-cost-of-the-banking-system-by-up-to-1-000-by-the-end-of-2018/)


### Komponent: NStratis

#### Krótki opis

##### NStratis is a fork of [NBitcoin](https://github.com/MetacoSA/NBitcoin) with additional support for:

- POS (Proof of Stake) mining algorithm
- Hash functions for the X13 POW mining algorithm

NStratis is targeted to the Stratis blockchain . 
It's the core component of the Stratis [FullNode](https://github.com/stratisproject/StratisBitcoinFullNode) framework, a port of the bitcoin blockchain in C#

* technologia **C#**
* Funkcja **BlockChain Development Framweork** *oficjalnie tak to nazwali; wstępny przegląd bardziej wygląda jak implementacja własnej kryptowaluty na bazie BitCoina*

#### Namiary

* Link do opisu biblioteki: [Stratis](https://stratisplatform.com/2016/11/18/start-coding-blockchain-apps-natively-in-c-and-net-with-stratis/)
* Link do kodu: [GitHub](https://github.com/stratisproject/NStratis)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *2*
* Możliwość równomiernego rozłożenia prac *3*
* Licencja *MIT*
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *[Stratis](https://stratisplatform.com/) (firma), ilość aktywnych developerów: 36*
* Ocena kodu przez społeczność
    * ilość gwiazdek - 40
    * ilość forków - 213
    * ilość osób śledzących - 18
    * ilość otwartych problemów - 2
    * aktywność projektu - 1755 commitów, 5 branchów, 36 kontrybutorów, ostatni commit: < 1 dzień temu
    *  *raczej nieprzydatne w początkowej fazie ze względu na nie do końca pasującą funkcję komponentu, jednak możliwe wykorzystanie pewnych fragmentów w etapie późniejszym, jak np: PoS*


#### Dodatkowe informacje

1. Przykładowe kody programowania BlockChain w .NET (w oparciu o NBitCoin, którego forkiem jest NStratis): [GitHub](https://github.com/ProgrammingBlockchain/ProgrammingBlockchainCodeExamples/)
2. Pdf "Blockchain Programming in C#": [link](https://aois.blob.core.windows.net/public/Blockchain%20Programming%20in%20CSharp.pdf)


## Java

### Komponent web3j

#### Krótki opis

web3j is a lightweight, reactive, type safe Java and Android library for integrating with clients (nodes) on the Ethereum network

Features:

* Complete implementation of Ethereum's JSON-RPC client API over HTTP and IPC
* Ethereum wallet support
* Auto-generation of Java smart contract wrappers to create, deploy, transact with and call smart contracts from native Java code
* Support for Parity's Personal, and Geth's Personal client APIs
* Support for Infura, so you don't have to run an Ethereum client yourself

#### Namiary

* [Strona domowa projektu](http://web3j.io)
* Video z omówieniem biblioteki: [Java and the Blockchain](https://www.youtube.com/watch?v=ea3miXs_P6Y)
* Link do kodu: [Github](https://github.com/web3j/web3j)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *1*
* Możliwość równomiernego rozłożenia prac *1*
* Licencja: *Apache License 2.0*
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *społeczny, ilość aktywnych developerów: 9*
* Ocena kodu przez społeczność
    * ilość gwiazdek - 221
    * ilość forków - 86
    * ilość osób śledzących - 45
    * ilość otwartych problemów - 23
    * aktywność projektu - 303 commitów, 4 branch, 18 kontrybutorów


### Eclipse RDF4J (poprzednio: Sesame)

#### Krótki opis

RDF4J udostępnia programowalne API, za pomocą którego można tworzyć modele RDF, dodawać i usuwać trójki, zapisywać do pliku i odczytywać (wspierane są różne formaty: RDF/XML, Turtle, N-Triples, Json-LD; cała dostępna lista [tutaj](http://docs.rdf4j.org/javadoc/latest/org/eclipse/rdf4j/rio/RDFFormat.html)). Przykłady użycia API można znaleźć pod [tym](https://github.com/eclipse/rdf4j-doc/tree/master/examples) adresem.

RDF4J udostępnia następujące aplikacje do zarządzania repozytoriami RDF:

* RDF4J Server - aplikację serwerową uruchamianą w kontenerze serwletów Javy. Stanowi back-end dla systemu zarządzania repozytoriami. Udostępnia końcówkę SPARQL-ową.
* RDF4J Workbench - front-end dla RDF Servera.
* RDF4J Console


#### Namiary

* [Strona domowa projektu](http://rdf4j.org/)
* [Repozytorium](https://github.com/eclipse/rdf4j)
* [Dokumentacja](http://docs.rdf4j.org/)


#### Ocena

* Możliwość wykorzystania dotychczasowych prac *1*
* Możliwość równomiernego rozłożenia prac *1*
* Licencja: *Eclipse Distribution License (EDL) v1.0*
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *Fundacja Eclipse, open source, ilość aktywnych developerów: 15*
* Ocena kodu przez społeczność (na podstawie GitHuba)
    * ilość gwiazdek - 83
    * ilość forków - 31
    * ilość osób śledzących - 19
    * ilość otwartych problemów - 245
    * aktywność projektu - 928 commitów, 7 branch, 15 kontrybutorów



### Apache Jena
Przy wyborze triplestore brana była pod uwagę platforma [Apache Jena](https://jena.apache.org) - SPARQL Endpoint Fuseki używający serializacji HDT (https://github.com/rdfhdt/hdt-java/tree/master/hdt-fuseki), jednak na tym etapie ze względu na szczegóły implementacyjne (w projekcie założono obecność w dużej liczby named graphs - w Apache Jena każdemu z nich odpowiada "otwarty plik", co przy ograniczeniach na liczbę jednocześnie otwartych plików, obecnych na poziomie systemów operacyjnych, stanowi istotny problem w skalowalności rozwiązania) zostało ono odrzucone.




#### Krótki opis

Apache Jena udostępnia programowalne API w Javie. Za pomocą API można tworzyć i modyfikować modele RDF, wczytywać je z plików i zapisywać do plików. Obsługiwane serializacje RDF można znaleźć w tutaj. Przykłady użycia API znajdują się w dokumentacji projektu oraz w innym naszym projekcie: SearchInsights.

Jena dostarcza również natywnego TS, który nazywa się TDB. Oprócz TDB, istnieje również możliwość użycia Fuseki jako serwera SPARQL, ale nie jestem pewien czy można komunikować się z nim bezpośrednio za pomocą programowalnego API (raczej nie).

#### Namiary

* [Strona domowa projektu](http://jena.apache.org/)
* [Repozytorium (Mirror)](https://github.com/apache/jena)
* [Dokumentacja](http://jena.apache.org/documentation/)
* [Javadoc](http://jena.apache.org/documentation/javadoc/)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *3*
* Możliwość równomiernego rozłożenia prac *1*
* Licencja: *Apache License 2.0*
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *Fundacja Apache, open source, ilość aktywnych developerów: 31*
* Ocena kodu przez społeczność (na podstawie GitHuba)
    * ilość gwiazdek - 340
    * ilość forków - 278
    * ilość osób śledzących - 63
    * ilość otwartych problemów - Brak danych
    * aktywność projektu - 5989 commitów, 2 branch, 31 kontrybutorów (na podstawie mirrora)


## JavaScript

### Komponent naivechain

#### Krótki opis

`naivechain` to implementacja prostego BC w języku JavaScript, wykorzystująca framework `node.js`, zawarta w ok. 200 liniach kodu. Nie jest to biblioteka do tworzenia BC, ale gotowa, choć bardzo prosta i ograniczona, implementacja BC. `naivechain` działa jako serwer HTTP oraz udostępnia web service'y do połączeń typu P2P pomiędzy poszczególnymi węzłami. Najważniejsze cechy tej implementacji to:

* Interfejs HTTP do zarządzania węzłami.
* Websockety używane do komunikacji z innymi węzłami (P2P).
* Komunikacja P2P używana do rejestrowania nowych węzłów i rozgłaszania nowych bloków.
* Blok składa się z: 
    - indeksu,
    - poprzedniego hasha,
    - timestampa,
    - danych (dowolny napis),
    - hasha: sha256(indeks + poprzedni hash + timestamp + dane)

#### Namiary

* Link do opisu biblioteki: [Opis na blogu autora](https://medium.com/@lhartikk/a-blockchain-in-200-lines-of-code-963cc1cc0e54)
* Link do kodu: [Github](https://github.com/lhartikk/naivechain)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *2*
* Możliwość równomiernego rozłożenia prac *1* (ew. *2* jeżeli weźmiemy pod uwage RR)
* Licencja: *Apache License 2.0*
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *społeczny, ilość aktywnych developerów: 9*
* Ocena kodu przez społeczność
    * ilość gwiazdek - 1692
    * ilość forków - 233,
    * ilość osób śledzących - 99
    * ilość otwartych problemów - 6
    * aktywność projektu - 9 commitów, 1 branch, 2 kontrybutorów


## C++

## Komponent: Ethereum C++ client

### Krótki opis

It is the third most popular of the Ethereum clients, behind geth (the go client) and Parity (the rust client). The code is exceptionally portable and has been used successfully on a very broad range of operating systems and hardware. [cpp-ethereum](http://www.ethdocs.org/en/latest/ethereum-clients/cpp-ethereum/)

### License
GNU General Public License v3.0 [GPL-3.0](https://raw.githubusercontent.com/ethereum/cpp-ethereum/develop/LICENSE)

* technologia **C++**
* funkcja **ethereum API**

### Namiary

* Repository: [GitHub re](https://github.com/ethereum/cpp-ethereum/)

### Ocena

* Możliwość wykorzystania dotychczasowych prac *5*
* Możliwość równomiernego rozłożenia prac *5*
* Licencja GPL-3.0
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *społeczny, ilość aktywnych developerów: ?*
* Ocena kodu przez społeczność (2017-07-14, godz. 09:00)
  * ilość gwiazdek - 1388
  * ilość forków - 949
  * ilość osób śledzących - 292
  * ilość otwartych problemów - 254
  * aktywność projektu - wysoka (??)


## WAŻNE [OWLchain](https://github.com/owlchain/owlchain-core)

## Komponent: HDT

### Krótki opis

HDT (Header, Dictionary, Triples) is a compact data structure and binary serialization format for RDF that keeps big datasets compressed to save space while maintaining search and browse operations without prior decompression. [HDT](http://www.rdfhdt.org)

 - The size of the files is smaller
 - The HDT file is already indexed
 - High performance querying
 - Highly concurrent
 - The format is open

 - C++ and Java libraries / command line tools to create and search HDT files.
 - HDT-it! GUI to create and browse HDT files from your desktop: [HDT-it! GUI tool](http://www.rdfhdt.org/downloads/)
 - Jena Integration to have a Jena Model on top of a given HDT file

 - Raptor RDF Parser Library 2.x (optional) This enables importing RDF data in many serialization formats, e.g., RDF/XML, Turtle, N3, etc

### License
 - The libraries are open source (LGPL)


* technologia **C++**
* funkcja **binary serialization format**

### Namiary

* HDT C++ Library and Tools: [GitHub](https://github.com/rdfhdt/hdt-cpp)
* HDT Java library and tools: [GitHub](https://github.com/rdfhdt/hdt-java)
* HDT integration with Jena: [howto](http://www.rdfhdt.org/manual-of-hdt-integration-with-jena/), [fuseki](http://www.rdfhdt.org/manual-of-hdt-integration-with-jena/#fuseki)

### Ocena

* Możliwość wykorzystania dotychczasowych prac *5*
* Możliwość równomiernego rozłożenia prac *5*
* Licencja LGPL
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *społeczny, ilość aktywnych developerów: ?*
* Ocena kodu przez społeczność (2017-07-14, godz. 09:00)
  * ilość gwiazdek - 31
  * ilość forków - 14
  * ilość osób śledzących - 19
  * ilość otwartych problemów - 8
  * aktywność projektu - niska (???)

## Komponent: Redland

### Krótki opis

Redland is a set of free software C libraries that provide support for the Resource Description Framework (RDF). [Redland](http://librdf.org/)


 - Modular, object based libraries and APIs for manipulating the RDF graph, triples, URIs and Literals.
 - Storage for graphs in memory and persistently with Oracle Berkeley DB, MySQL 3-5, PostgreSQL, OpenLink Virtoso, SQLite, files or URIs.
 - Support for multiple syntaxes for reading and writing RDF as RDF/XML, N-Triples and Turtle, RSS and Atom syntaxes via the [Raptor RDF Syntax Library](https://github.com/dajobe/raptor).
 - Querying with SPARQL and RDQL using the [Rasqal RDF Query Library](https://github.com/dajobe/rasqal).
 - Data aggregation and recording provenance support with Redland contexts.
 - Language Bindings in Perl, PHP, Python and Ruby via the [Redland Bindings](https://github.com/dajobe/redland-bindings) package.
 - Command line utility programs rdfproc (RDF), rapper (parsing) and roqet (query).
 - Portable, fast and with no known memory leaks.

### License

All Redland packages are free software / open source software and released under the LGPL 2.1, GPL 2 or Apache 2 licenses as alternatives.
See the individual package license files for full details and any exceptions.

1. The GNU Lesser General Public License (LGPL) Version 2.1 or any newer version [lgpl-2.1](http://librdf.org/COPYING.LIB)
2. GNU General Public License (GPL) V2 or any newer version [gpl-2](http://librdf.org/COPYING)
3. The Apache License V2.0 or any newer version [asl-2.0](http://librdf.org/LICENSE-2.0.txt)


* technologia **C**
* funkcja **triplestore API**

### Namiary

* Building and Installing from Source: [install](http://librdf.org/INSTALL.html)
* Source: [librdf](http://download.librdf.org/source/), [GitHub](https://github.com/dajobe)

### Ocena

* Możliwość wykorzystania dotychczasowych prac *?*
* Możliwość równomiernego rozłożenia prac *?*
* Licencja LGPL/GPL/Apache
* Dostęp do kodu źródłowego *czytaj, pull request, fork*
* Właściciel kodu *społeczny, ilość aktywnych developerów: ??*
* Ocena kodu przez społeczność (2017-07-14, godz. 09:00) - różne oceny dla poszczególnych modułów kodu (librdf, rasqal, raptor, redland-bindings)
  * ilość gwiazdek - 63
  * ilość forków - 18
  * ilość osób śledzących - 11
  * ilość otwartych problemów - <brak>
  * aktywność projektu - średnia (???)


### Projekty używające modułów Redland
* owlcpp is an open-source C++ library for parsing, querying, and reasoning with OWL 2 ontologies. [owlcpp](http://owl-cpp.sourceforge.net/) [opis](https://jbiomedsem.biomedcentral.com/articles/10.1186/s13326-015-0035-z)
* BRAHMS is designed as a fast main-memory RDF/S storage [BRAHMS](http://lsdis.cs.uga.edu/projects/semdis/brahms/), [The Semantic Web](https://books.google.pl/books?id=bSIHCAAAQBAJ&pg=PA436&lpg=PA436&dq=brahms+raptor&source=bl&ots=Byi10LhtTJ&sig=YBLYu4q87hAiQpZT6Px1kunculA&hl=pl&sa=X&ved=0ahUKEwjwjdT38YXVAhWmHpoKHWMyAW8Q6AEITTAH#v=onepage&q=brahms%20raptor&f=false)
* Soprano (formally known as QRDF) is a library which provides a nice Qt interface to RDF storage solutions [Soprano](https://sourceforge.net/projects/soprano/)


## Wzór

### Komponent: <nazwa>

#### Krótki opis

* technologia **język/środowisko**
* Funkcja

#### Namiary

* Link do opisu biblioteki: [Nazwa](https://confluence.makolab.net/display/EBN/EXT+-+Blockchain+-+NCBR)
* Link do kodu: [Nazwa](https://confluence.makolab.net/display/EBN/EXT+-+Blockchain+-+NCBR)

#### Ocena

* Możliwość wykorzystania dotychczasowych prac *ocena 2..5*
* Możliwość równomiernego rozłożenia prac *ilość potencjalnych developerów*
* Licencja [MIT, .....]
* Dostęp do kodu źródłowego *brak, czytaj, czytaj/pisz, pull request, fork, itp*
* Właściciel kodu *firma, społeczny, ilość aktywnych developerów*
* Ocena kodu przez społeczność
	* ilość gwiazdek
	* ilość forków,
	* ilość osób śledzących
	* ilość otwartych problemów
	* aktywność projektu