## Example stories [[Storytelling]]
### Andrey tells about working expirience

Principal frontend developer

December 2015 — Until now (6 years and 1 month)

I participated in the following projects:

**Frontend for public part of public platform one of the largest russian bank(2015-2018)  
**I started working on this project, when it was being begun redesinging completly. Only at frontend side, 100+ developers and 10+ were involved with the project. Codebase had 300+ KLoC. I had several accomplishments on this project:  
  
- i've begun to introduce unit-testing in my team and promoted it on cross-team level. I wirtten base utils for unit-testing, first reference examples of unit-tests and guides for writing tests. All teams had used this utils, examples and guides, as long as project was switched to another testing library(Enzyme)
  
- I've enhanced our build system. I enhanced and fixed several babel plugins ([for example babel-plugin-ramda](https://github.com/megawac/babel-plugin-ramda/pull/12)). During this process, I was finding bugs in Babel and commiting tests and issues in [Babel repo] (https://github.com/babel/babel/pull/3495)  
  
- I've introduced using functional concepts such as Lens and Iso for working with hierarchical data structures. Its tools helped us worked with complex normalized immutable data structures without boilerplate. Also, this tools ensured consistency when we were updating and normalizing/denormalizing our data 
  
- I've built my own library for working with hierarchical forms
  
- I've promoted using typechecker for our codebase. I written codemod for converting react app to Flowtype, which was tailored for project's features. Also, I promoted using contract system(tcomb, runtypes) for specification external data and more gradual transition on typed JS
  
- I've built PoC using property-based testing for testing core properties of our system
  
- I've proposed different ways to enhace architecture of our app. I've promoted fractal/onion architecture and built PoC of ["fractal redux connector library"](https://github.com/typeetfunc/redux-fractal-connect)   
  
**MVP of stocks dashboard(terminal) for fintech startup(2018)  
**It was small and short project(1,5 month). I've built interactive and real-time dashboard for trade in assets. I've used React and MobX for this. It was proof-of-concept of new expiremental feature for our client's main product.  
  
**Frontend of cybersecurity product for central banks for investigating cybersecurity issues and incidents(2018-2020)  
**I started working on project when project was being switched to angular2+. Also, project had changed business goals and ui/ux paradigm. Project was being developed by several medium(less than 5 people) teams. Project contained approximately 100KLoC. I had several big responsibilities on this project:  
  
- developing architecture decisions about developing of UI-kit for all projects of this company.  I've written desing document about all aspects of UI-Kit: requirements analysis, making demo/stage enviroment, connection between UI/UX tools and program code, organization design tokens and UI/UX guidelines, developing architecture of styles and distribution packages of UI-Kit. After all, this document was used by UI-Kit's team and used as base for more detailed RoadMap of this UI-Kit 

 - developing and integration plugin-based architecture for angular application. Plugins were placed at separated repository and could be edited by developers of external company. Bacause of this, we had to develop own version control system with the ability to "hot" replace and rollback each plugin in production enviroment also 
  
- integration monorepo tools(lerna) in project's pipeline and reorganization of building tools

**Frontend of user-customized dashboards system for geological prospecting of big goverment corporation in oil and gas sector(2020-2021) ** 
**This project consisted of UI-Kit and user-customized dashboards system. User was able to change set of widgets and their properties dynamically. Because of it project had to be able to migrate user UI config when component API were changing.  I've made general business-tasks on this project but also I've solved several big infrastructure issues:  
  
- I've switched unit-testing of components from enzyme to testing-library. Also, I've enhaced linting on project. In order to achieve this, I've contributed to several eslint plugins([for example eslint-plugin-spellchecker](https://github.com/aotaduy/eslint-plugin-spellcheck/pull/68))

**-** I've enhanced our migration system and contributed to  [react-grid-layout](https://github.com/react-grid-layout/react-grid-layout/pull/1303) to that end
  
- I've built docker container and written config of docker compose for transfer project to our client on the end of development
  
**UI-Kit of large airline (2021-to the present)  
**UI-Kit of company(80+ components) which is used by all company's projects(20+ different projects). My main responsibilities are review code, statement and decomposing tasks, intergration new tools and architecture decisions, process and pipeline optimizition, intergration new rules and metrics for developers, and research problem areas in our project.**  

**Also, I've participated in DevRel/Mentoring/HR activities in our company:**  
- I've helped to build process of skills assessment, ondoarding and assintance in engineer skills growth for company employees. I've interviewed job applicants and conducted perfomance-reviews. I've interviewed more than 100 applicants from junior to senior level and conducted more than 20 perfomance-reviews with developers from middle to principal level. Also I've conducted one-to-one, built test tasks, built our grade system and methodology for interviewing and conducting perfomance-review  
- I've developed basic methodology and structure of  [CSSSR.School](https://school.csssr.com/ru)  courses
- I've participated in development reference linting system for using inside our company  
- I've given talks on internal conference in our company
- I've participated in media activities of our company. I've made [video](https://youtu.be/KLsJOtGDWZY), [podcasts](https://youtu.be/oLguQIvqZ6s), [collaboration with external projects](https://youtu.be/Awnog8KYub4), [articles](https://blog.csssr.com/ru/article/side-effects/). I am one of the permanent speakers and original authors of podcasts [Argumentarium](https://youtu.be/7bJlNHtSqlM) and [Callback Hell](https://youtu.be/kdv9Kjrslr0)

Сентябрь 2013 — Ноябрь 2015 (2 года и 3 месяца)
-   10.2013 - 04.2014 - разработка API для маркетплейса цифровых товаров, а также решение инфраструктурных задач(например написание библиотеки для работы с Oauth и API социалок)
-   04.2014 - 10.2014 - поддержка legacy проекта(система множества интернет магазинов по продаже цифровых товаров) и одновременное переписывание и перепроектирование его с нуля на новой основе. Здесь помимо бекенда пришлось глубоко погрузится во фронтенд - мной была сделана новая админка по управлению всей системой
-   10.2014-01.2015 - временно переключился на написание javascript для маркетплейса(в основном это касалось интеграции бекенда с фронтендом)
-   01.2015-11.2015 - запуск и поддержка(бекенд+фронтенд+администрирование) второго проекта(системы магазинов). Помимо разработки фич и багфиксов, занимался инфраструктурными задачами - переход к feature-based версионированию и автоматизированному деплою, централизованному логгированию(fluentd/graylog2), использованию ansible([https://github.com/typeetfunc/ansible-experiments](https://github.com/typeetfunc/ansible-experiments)) для создания и управления узлами приложения.
-   помимо этих проектов постоянно участвовал в доработке корпоративных библиотек(фреймворка([https://github.com/typeetfunc/pef-front-psgi-dist](https://github.com/typeetfunc/pef-front-psgi-dist)) и библиотек для логгирования([https://github.com/typeetfunc/pef-log](https://github.com/typeetfunc/pef-log)) и доступа к данным), делал прототип аггрегатора интернет-супермаркетов(включающего парсинг каталога крупных магазинов при помощи phantom.js и кластеризация товаров по признакам)