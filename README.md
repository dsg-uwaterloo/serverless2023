<!--- # Workshop on Serverless Data Analytics 
## 1 September 2023, Vancouver, Canada
### (Co-located with VLDB 2023 Conference)
-->
Serverless computing has become popular with cloud providers because of its ease of use by application developers, its lightweight runtime, ease of maangement, resource elasticity and fine-grained billing. Adapting data analytics applications to serverless platforms pose new challenges. To maximize the benefits of serverless, the data analytics systems must be well designed, implemented, maintained, and optimized to efficiently process the massive amount of intermediate data, achieve the best possible job performance with a limited budget, minimize the cost without violating the QoS objective, etc. Recent work on serverless analytics has demonstrated the benefits of serverless architectures for resource- and cost-efficient data analytics. 

This workshop aims to focus on these problems, both from application development side and serverless system infrastructure side. It aims to bring together researchers and practitioners from data analytics and serverless computing communities to address the emerging need for serverless data analytic systems and applications. We welcome new ideas and critical research on Serverless Data Analytics as well as reports on best practices.

### Topics

The topics covered in the workshop include, but are not limited to:

* Serverless architecture for data analytics
* Task scheduling for serverless analytics
* Intermediate storage systems for serverless analytics
* Fine-grained resource allocation for serverless analytics
* High performance runtime for serverless analytics
* Query optimization in a serverless environment
* Data caching for serverless analytics

### Workshop Program

The workshop will have one keynote and 3-4 accepted papers with sufficient time for discussions.

**Keynote Speaker:** Gustavo Alonso, ETH Zürich

*Title*: The promise and the reality of serverless

*Abstract*: Serverless has captured the attention of researchers and practitioners alike for its promise of addressing several of the inefficiencies of current cloud computing platforms. Cloud providers tout it as a more efficient, simpler, and flexible way to deploy a restricted set of applications over large scale computing facilities. Some researchers consider it the next step in the evolution of the cloud and nothing sort of a revolutionary new computing platform. Many different versions of serverless, commercial and open source, are appearing, often with many different characteristics. There is also a growing body of research exploring multiple aspects of FaaS platforms and its applicability to a variety of use cases. In this talk I will argue that, on the research side, it is important to transcend the platforms available today and think about serverless in a much broader context, especially when the use case is data analytics. Rather than trying to adapt data processing to the quirks and vagaries of today’s offerings, we should explore how serverless should be to better serve the needs of data analytics and related use cases.  In the talk I will argue for a different approach to serverless data analytics, one more focused on making serverless work for data scientist rather than on removing features, limiting scope, or hacking around restrictions of current offerings.  

*Bio*: Gustavo Alonso is a professor in the Department of Computer Science of ETH Zurich where he is a member of the Systems Group. He graduated from the Technical University of Madrid, Spain and did his MSc and PhD at the University of California at Santa Barbara. He was a research scientists at the IBM Almaden Research Center in San Jose, California before joining ETH. His research interests include data management, distributed systems, cloud computing architecture, and hardware acceleration through reconfigurable computing. Gustavo has received 4 Test-of-Time Awards for his research in databases, software runtimes, middleware, and mobile computing. He is an ACM Fellow, an IEEE Fellow, a Distinguished Alumnus of the Department of Computer Science of UC Santa Barbara, and has received the Lifetime Achievement Award from the European Chapter of ACM SIGOPS (EuroSys).

### Accepted Papers

* Hyperspecialized compilation for serverless functions, Leonhard Spiegelberg (Brown University); Tim Kraska (MIT); Malte Schwarzkopf (Brown University) 
* Ephemeral Per-query Engines for Serverless Analytics, Michal Wawrzoniak (ETHZ); Rodrigo Bruno (Instituto Superior Técnico / INESC-ID Lisboa); Ana Klimovic (ETH Zurich); Gustavo Alonso (ETHZ)
* BabelMR: A Polyglot Framework for Serverless MapReduce, Thomas Bodner (Hasso Plattner Institute, University of Potsdam); Fabian Mahling (Hasso Plattner Institute, University of Potsdam); Paul Rößler (Hasso Plattner Institute, University of Potsdam); Tilmann Rabl (HPI, University of Potsdam)

### Paper Submission & Evaluation 

Paper submission is to be done through CMT at the following site: <a href="https://cmt3.research.microsoft.com/SDA2023" target="_blank">https://cmt3.research.microsoft.com/SDA2023</a>

All papers will be peer reviewed by the Program Committee. The submitted papers should not have been previously published or concurrently under consideration. Work-in-progress papers that are shorter in length are acceptable and encouraged. The workshop will be in-person and one author of each paper is required to register.

Regular papers are 12 pages (excluding references); shorter, work-in-progress papers are limited to 6 pages (excluding references). PVLDB formatting guidelines and styles apply. Please consult <a href="http://vldb.org/pvldb/volumes/17/formatting" target="_blank">http://vldb.org/pvldb/volumes/17/formatting</a> for templates.

### Important Dates

* Papers due: ~~22 June 2023, midnight EST~~ 30 June 2023, midnight EST
* Author notification: ~~15 July 2023~~ 30 July 2023
* Camera-ready: ~~22 July 2023,~~ midnight EST 9 August 2023

### Proceedings

There will be a joint proceedings of most VLDB 2023 workshops and SDA papers will be included in it. The proceedings will be published as part of CEUR-WS.

### Organizers
* M. Tamer Özsu, University of Waterloo (tamer.ozsu@uwaterloo.ca)
* Xun Xue, Huawei Technologies Canada (xun.xue@huawei.com)

### Program Committee Members

* Ashraf Aboulnaga, Qatar Computing Research Institute
* Gustavo Alonso, ETH Zürich
* Samer Al-Kiswani, University of Waterloo
* Khuzaima Daudjee, University of Waterloo
* Niv Dayan, University of Toronto
* Schahram Dustdar, TU Wien
* Robin Grosman, Huawei Technologies Canada
* Alexandru Iosup, Vrije Universiteit Amsterdam 
* Guoliang Li, Tsinghua University
* Samuel Madden, MIT
* Mohammad Shahrad, University of British Columbia
* Jianguo Wang, Purdue University
