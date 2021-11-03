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
            Some info about you. Pellentesque in ipsum id orci porta dapibus. Cras ultricies ligula sed magna dictum porta. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Sed porttitor lectus nibh.
            </p>
        {{< /resume-entry >}}

{{< social >}}
        
    {{< /resume-section >}}
    

    {{< resume-section title="Education" >}}
        {{< resume-entry what="Bachelor's program of Computer Science"
                         where="Sidney University"
                         when="2010–2013">}}
            <ol>
                <li> Some comment on what skills you learned</li>
                <li> Some other comment </li>
            </ol>
        {{< /resume-entry >}}
    {{< /resume-section >}}
{{< /container >}}
