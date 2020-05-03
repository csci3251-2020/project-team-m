 <h1>Introduction</h1>
 <p> Here's a short summary of things my team will do according to the tasks inside the issues folder: </p>
 <p> We have already started issues and created a project board. Once the README.md file is set up, we will show our team to the Internet,
 ensure that pull requests are added in the correct columns, write a code in C, update the web page https://csci3251-2020.github.io/, and lastly promote our repo </p>
 <h1>Code</h1>    
 <p>{% include_relative code.c %}</p>
 <p>![](https://github.com/csci3251-2020/project-team-m/workflows/CI/badge.svg) </p>
 <h1>Contributors</h1>  
{% for member in site.stu %}
  ![pic]({{ member.image }}){:height="50px" width="50px"}@{{ member.user }}({{member.name}})  
    {{ member.content ｜ markdownify }}  
{% endfor %}

---
Last updated: {{ site.time }}
