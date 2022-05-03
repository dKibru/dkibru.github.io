---
title: "Resume"
date: 2021-10-28T09:41:33+03:00
draft: false
menu:
  main:
    identifier: "resume"
    name: "Resume"
    weight: 5
---


{{< container >}}
    {{< resume-section title="About Me" >}}
        {{< resume-entry >}}
            <p>
            I am a  full Stack developer obsessed about developing SAAS products. 
            </p>
        {{< /resume-entry >}}

{{< social >}}
        
    {{< /resume-section >}}
    

    {{< resume-section title="Work Experience" >}}
        {{< resume-entry what="Full stack developer"
                         where="1888 Entrepreneurship Studio"
                         when="Dec 2021 - Present">}}
            <ul>
                <li>Developing and maintaining multiple codebases using nest.js and react.js</li> 
                <li>A little bit dev-opish work using aws resources such as lambda, ec2, amplify and rds</li>
                <li>Creating and maintaining Wordpress plugins.</li>
                <li>Migrating Wordpress plugins and themes to nest js and react.js</li>
            </ul>
        {{< /resume-entry >}}

        {{< resume-entry what="Exploit Researcher"
                         where="Information Network Security Agency ( INSA )"
                         when="Aug 2021 - Jan 2022">}}
        {{< /resume-entry >}}

        {{< resume-entry what="Lead developer and Co-founder"
                         where="Mala Tech Solutions"
                         when="Jan 2021 - Dec 2021">}}
            <ul>
                <li>Developed a multitenant custom ERP software for churches using laravel, vue.js, and inertia js <a href="https://church.et" target="_blank">church.et</a></li> 
                <li>Developed a microsoft office vsto plugin using c#. The plugin serves as a spelling checker for Sidaamu Afoo language.</li>
            </ul>
        {{< /resume-entry >}}

        {{< resume-entry what="Volunteer full-stack developer"
                         where="Adama Science and Technology University Deliverology Center"
                         when="Feb 2017 - Mar 2018">}}
            <ul>
                <li>Developed a staff evaluation system using laravel and vue.js</li> 
            </ul>
        {{< /resume-entry >}}
    {{< /resume-section >}}


    {{< resume-section title="Education" >}}
        {{< resume-entry what="Bachelor's program of Computer Science and Engineering"
                         where="Adama Science and Technology University"
                         when="Sept 2015 - Dec 2020">}}
            <ol>
                <!-- <li> Some comment on what skills you learned</li> -->
                <!-- <li> Some other comment </li> -->
            </ol>
        {{< /resume-entry >}}
    {{< /resume-section >}}
{{< /container >}}
