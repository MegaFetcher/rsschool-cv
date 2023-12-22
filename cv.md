
<style>
a {color: deepskyblue}
strong {color: coral}
em {color: springgreen}
pre code {color: mediumseagreen}
th {background-color: #2F2F2F; color: springgreen}
td {background-color: #2F2F2F; color: white}
div {background-color: #404040; color: white; padding:50px}
blockquote {color: white}
</style>

# **MegaFetcher**

- _Email_: [my_certification_mfsft@outlook.com](mailto:my_certification_mfsft@outlook.com)  
- _Discord_: **megafetcher**  
- _Languages_: Russian - _native_, Serbian /_B1_, English /_C1_, German /_B2_

## Vision

- _Developing_ convenient/comfortable app interfaces - web and mobile

## Tech. Stack

- _Langiuages/Frameworks_:
  VBA, Java, Java-Script, Type-Script, SQL, HTML, CSS, XML/XSD, JSON, YAML, OPEN API, Angular, React.JS, Open API, Pascal, Assembler  
- _Tools_: IntelliJ IDEA, Visual Studio Code, Node.js, NPM, Redis, Apache Cassandra, PostgreSQL, Postman, FIGMA, Jira/Confluence/Bitbacket, GitHub, GitLab, Azure Cloud, Azure DevOps, Lucid Chart, Enterprise Architect  
- _Methodologies_: SAFe, Scrum, Kanban

## Education

1998 - 2000
![OSU](https://megafetcher.github.io/cv/src/osu.jpg) 
[Oklahoma State University](https://okstate.edu), USA - FIN/MIS   
1993 - 1997
![TPU](https://megafetcher.github.io/cv/src/tpu.jpg) 
[Tomsk Polytechnic University](https://www.tpu.ru), RUSSIAN FEDERATION - MGMT

## Educational Programs

10/2023 - Scope Change Management - Best Practices  
07/2023 - Azure Fundamentals of Microsoft  
04/2023 - BA Intermediate Mentoring Program    
07/2018 - Mechanisms of "1S:Enterprise 8" platform  
08/2012 - Legal Aspects of Corporate Lending  
11/2008 - Business Valuation BV201/BV202 ASA   
05/2006 - Initial Level exam for Financial market specialists   
11/2001 - Private Equity Management of EVCI  


## Professional Experience

 | Tenure      | Domain    | Position      |
 |:-           |:-:        |:-:            |
 | 2019 - curr.| IT        | BA            |
 | 2018 - 2019 | IT        | BA            |
 | 2017 - 2018 | AUDIT     | Auditor       |
 | 2014 - 2017 | CORP FIN  | Specialist    |  
 | 2011 - 2013 | BANKING   | Specialist    |  
 | 2008 - 2010 | CORP FIN  | Manager       |  

## Hobbies
![Swimming](https://megafetcher.github.io/cv/src/Evening_Swim.jpg)


## Code Example

``` //javascript
let counter_1 = 0           // counter of the requests
var set_1 = new Set()       // set to collect unique values
var array_1 = new Array()   // array to pass unique values into function
array_1 = Array.from(set_1)

function sendRequestsSequentially (array_1, counter_1) {

    if (counter_1 < array_1.length-0) {
        var stringa_1 = {
            method:,
            url:,
            header:{
                'Content-Type':,
                'Authorization:'
            },
            body: {
                mode:,
                raw: JSON.stringify({'key': array_1[counter_1]})
            }
        }
        pm.sendRequest (stringa_1, (err, response) => {
            
            if (err) {
                console.error(err)
            }

            console.log(counter_1 + '. Request parameter: ' + array_1[counter_1].toString())
            var stringa_2 = JSON.stringify(JSON.parse(response.text()), null, 2)
            pm.visualizer.set("Response received:", stringa_2)

            setTimeout(() => {
                sendRequestsSequentially(array_1, counter_1 + 1)
            }, 5000) // 5 sec
        })
    }
}
```