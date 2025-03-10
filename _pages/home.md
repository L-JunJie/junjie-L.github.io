---
title: "Wenbo Huang (黄文博) - Homepage"
layout: gridlay
excerpt: "Wenbo Huang"
sitemap: false
permalink: /
---

<!-- <div id="top"></div> -->
<div class="container-fluid">
<div class="row">
<div class="col-sm-8">

### **About <font color="#00d1ff">Me</font> (Xero)**
I come from Nanjing, Jiangsu, China, where is known as 'Capital of Six Dynasties' and 'City of Stone'. I was a <del>script kiddie</del> and received the 
B.S. degree from <a href="http://www.njtech.edu.cn/" target="_blank">Nanjing Tech University</a>, Nanjing, China, in 2019. I received the M.S degree with the supervision by <a href="http://leizhangnjnu.github.io" target="_blank">A.P Lei Zhang</a> 
from <a href="http://www.njnu.edu.cn/" target="_blank">Nanjing Normal University</a>, Nanjing, China, in 2022. Now I am a Ph.D student under the Excellent Ph.D Training Program 
and pursuing my degree in
<!-- <a href="http://palm.seu.edu.cn/" target="_blank">PAttern Learning and Mining (PALM) Lab</a>, -->
<a href="https://cse.seu.edu.cn/" target="_blank">School of Computer Science and Engineering</a>, <a href="https://www.seu.edu.cn/">Southeast University</a>,
Nanjing, China. 
<br>
My research interests including Video Understanding and Ubiquitous Computing, especially focus on few-shot video action recognition. I am also an <a href="{{ site.url }}{{ site.baseurl }}/images/pages/animal lover.jpg">animal lover</a>. <font color="white">PS：为了更新简历，我还tm花99买了超级简历的终生会员。</font>
<!-- By the way, I must express my gratitude to <a href="https://sci-hub.se/alexandra">Alexandra Elbakyan</a>. The website built by her helps me much on paper writing and search.
Everyone can find the papers they need <a href="https://sci-hub.st/">here [Sci-Hub]</a>. -->
<br>

<!-- ### **Notice**
欢迎先阅读这个<a href="https://wenbohuang1002X.github.io/document">文档</a>。
<br>
Welcome to read this <a href="https://wenbohuang1002X.github.io/document">document</a>. -->
<!-- <del>Select the part inside the arrow to reveal the hidden content.</del> -->

<!-- <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?w=128&d=Xit1o4P9tPO4V5F-vf13Il6mKflR-sERYSPiKcWoLcM"></script> -->

<!-- ### **Skills & Hobbies (Sort by Proficiency)**

#### **Skills**
* Languages
    - Python (PyTorch, Jittor, Keras, TensorFlow).
	- C#, LaTeX.
	- SQL, Kotlin.

#### **Hobbies**
* Sports
    - Cycling.
	- Rope Skipping.

* Recreation
    - Drum Set.
	- Card Game (OCG like Yo☆Gi☆Oh).
	- Drawing. -->


### **CV**
You can download my latest CV (<a href="https://wenbohuang1002X.github.io/papers/resume/Wenbo Huang's CV.pdf" target="_blank">English Version</a> and <a href="https://wenbohuang1002X.github.io/papers/resume/黄文博的简历.pdf" target="_blank">Chinese Version</a>).<br>
CV was last updated on 2022.7.22. <br>
<!-- <pre>
                            CV was last updated on October 25, 2021.
　　　　　／＞＿＿＿フ       
　　　　　|  　_　 _|   
　 　　　／  ミ  ˇ ノ  
　　 　 /　　　 　 |
　　　 /　 ヽ　　 ﾉ
　 　 │　　|　|　|
　／￣|　　 |　|　|
　| (￣ヽ＿_ヽ_)__)
　＼二つ
</pre> -->

### **News** 
{% for article in site.data.news limit:4 %}
{{ article.date }} :
<em>{{ article.headline }}</em>
{{article.news}}
{{article.hot}}
{% endfor %}

#### <a href="{{ site.url }}{{ site.baseurl }}/allnews" class="btn-xs btn-success">See All News</a>
<!-- #### <a href="#top" class="btn-xs btn-primary">Go Back to Top</a> -->

</div>

<div class="col-sm-4" style="display:table-cell; vertical-align:middle; text-align:center">

  <ul style="overflow: hidden">
  <a href ="{{ site.url }}{{ site.baseurl }}/experience"> <img src="{{ site.url }}{{ site.baseurl }}/images/pages/adminRX.jpg" class="img-responsive" width="100%" alt="我自己"/></a>
  </ul>

  <!-- <br clear="all" /> -->

  Wenbo Huang (The left one)<br> 
  
  黄文博 (左一)<br> 
  
  211189 post code, Unknown room, Computer Building, Jiulong Lake Campus (<a href="https://j.map.baidu.com/d6/Gugf">Maps</a>).<br>

  <a href="https://cse.seu.edu.cn/" target="_blank">School of Computer Science and Engineering</a>.<br>
  
  <a href="http://www.seu.edu.cn/" target="_blank">Southeast University (SEU)</a>.<br> 
  
  Nanjing, Jiangsu, China. <br> 
  
  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=200&t=tt&d=8-DvOgF_lbECI1LW2zYseuVsLWocq2FTI6ih18Dk81g&co=0095ff&cmo=ff6200&cmn=00ff00&ct=000000'></script>
  
</div>

</div>
</div>

<div class="col-sm-12">

### **Publications (<font color="red">Journal Papers</font> <font color="green">&</font> <font color="blue">Conference Papers</font>)**

<!-- #### * means corresponding authors -->

{% for publi in site.data.publist limit:100 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="200px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>
 
 <p>{{ publi.name }}</p>
 
 <p>{{ publi.DOI }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 {% endif %}
 
 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a>
 <a href="{{ publi.link5.url }}" target="_blank" class="btn btn-warning">{{ publi.link5.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 6 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a>
 <a href="{{ publi.link5.url }}" target="_blank" class="btn btn-warning">{{ publi.link5.display }}</a>
 <a href="{{ publi.link6.url }}" target="_blank" class="btn btn-danger">{{ publi.link6.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<br clear="all"/>

#### <a href="{{ site.url }}{{ site.baseurl }}/publications" class="btn-xs btn-success">See All Publications</a>

</div>

<div class="col-sm-12">

<!-- #### <a href="#top" class="btn-xs btn-primary">Go Back to Top</a> -->

### **Theses**

{% for publi in site.data.theseslist limit:6 %}

<div class="col-sm-11 clearfix">
 <div class="well">
 <pubtit>{{ publi.title }}</pubtit>

 <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="180px" style="float: left" />

 <p>{{ publi.description }}</p>

 <p><em>{{ publi.authors }}</em></p>

 <p>{{ publi.venue }}</p>
 
 <p>{{ publi.name }}</p>
 
 <p>{{ publi.DOI }}</p>

 {% if publi.number_link == 1 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 {% endif %}
 
 {% if publi.number_link == 2 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 3 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 4 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 5 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a>
 <a href="{{ publi.link5.url }}" target="_blank" class="btn btn-warning">{{ publi.link5.display }}</a></p>
 {% endif %}
 
 {% if publi.number_link == 6 %}
 <p><a href="{{ publi.link1.url }}" target="_blank" class="btn btn-default">{{ publi.link1.display }}</a>
 <a href="{{ publi.link2.url }}" target="_blank" class="btn btn-primary">{{ publi.link2.display }}</a>
 <a href="{{ publi.link3.url }}" target="_blank" class="btn btn-success">{{ publi.link3.display }}</a>
 <a href="{{ publi.link4.url }}" target="_blank" class="btn btn-info">{{ publi.link4.display }}</a>
 <a href="{{ publi.link5.url }}" target="_blank" class="btn btn-warning">{{ publi.link5.display }}</a>
 <a href="{{ publi.link6.url }}" target="_blank" class="btn btn-danger">{{ publi.link6.display }}</a></p>
 {% endif %}

 </div>
</div>

{% endfor %}

<p> &nbsp; </p>

</div>

<!-- #### <a href="#top" class="btn-xs btn-primary">Go Back to Top</a> -->

### **Academic Related**

#### **Academic Service**
* **Journal Reviewer**
	- <a href="https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=69">IEEE Transactions on Knowledge and Data Engineering</a>, 2023.
	- <a href="https://www.sciencedirect.com/journal/neurocomputing">Elsevier Neurocomputing</a>, 2023.
	<!-- - <a href="https://www.tandfonline.com/journals/ucbs20/">Cybernetics and Systems</a>, 2023. -->
	<!-- - <a href="https://www.springer.com/journal/11063/">Neural Processing Letters</a>, 2023. -->
	- <a href="https://www.nature.com/srep/">Scientific Report</a>, 2022.
	<!-- - <a href="https://www.tandfonline.com/journals/yims20">The Imaging Science Journal</a>, 2022. -->
	<!-- - <a href="https://benthamscience.com/journals/current-computer-aided-drug-design">Current Computer-Aided Drug Design</a>, 2022. -->
    <!-- - <a href="https://www.mdpi.com/journal/sensors">MDPI Sensors</a>, 2021. -->

* **Conference Reviewer**
	<!-- - <a href="http://www.iccbbs.org/">International Conference on Computational Biology and Biomedical Science (CBBS 2022)</a>, 2023. -->
	<!-- - <a href="http://www.icctis.org/">International Conference on Computer Technology and Information Science (CTIS 2023)</a>, 2023. -->
	<!-- - <a href="http://www.iceeep.org/">The Seventh International Conference on Energy Engineering and Environmental Protection (EEEP2022)</a>, 2022. -->
    - <a href="http://www.csaeconf.org/">ACM The 6th International Conference on Computer Science and Application Engineering (CSAE 2022)</a>, 2022, <a href="https://wenbohuang1002X.github.io/papers/CSAE2022 Certificate of Appreciation_Wenbo Huang.pdf">Certificate</a>.
	<!-- - <a href="http://www.icoice.org/">International Conference on Optoelectronic Information and Computer Engineering (OCIE 2022)</a>, 2022. -->
	
* **Book Reviewer**
    - Book entitled--'Digital Innovation Adoption: Architectural Recommendations and Security Solutions', 2022.

* **Teaching Activity**
	- Teaching assistant of Operating System (bilingual instruction), Spring 2023, Southeast University.
	<!-- - Teaching assistant of Edu-By: The Time of Robotics - Artificial Intelligence and Social Change (博雅课：机器人时代 - 人工智能与社会变革), Fall 2021, Nanjing Normal University. -->
	<!-- - Teaching assistant of Artificial Intelligence and Big Data, Spring 2022, Nanjing Normal University. -->
	<!-- - Security Administrator for the Institute of Information and Control Technologies, School of Electric and Autumation Engineerning, 2020-2021, Nanjing Normal University. -->

#### **Award & Honor**
* **Scholarship**
	- Freshman Scholarship (Excellent Ph.D Training Program, total 50), 2022, Southeast University, <a href="https://wenbohuang1002X.github.io/papers/2022freshman.pdf">Certificate</a>.
    - National Scholarship for Postgraduate Students (rank 1, total 65), 2021, The Chinese Ministry of Education (MOE), <a href="https://wenbohuang1002X.github.io/papers/2021national.pdf">Certificate No.SSY202120653</a>.
	- First-class Academic Scholarship (rank 6, total 65), 2021, Nanjing Normal University.

<!-- * **Competition** 
    - Provincial Third Prize, The 17th 'Challenge Cup' National University Student Extracurricular Academic Science and 
	Technology Works Competition 'Science and Technology' Special Competition, 2021, Jiangsu Province/Central Committee of the Communist Youth League/China Association for Science and Technology/The Chinese Ministry of Education (MOE)
	/Chinese Academy of Social Sciences/National Federation of Students. -->

* **Honor**
	- Outstanding graduate, 2022, Nanjing Normal University, <a href="https://wenbohuang1002X.github.io/papers/2022graduate.pdf">Certificate</a>.
	- Outstanding postgraduate (rank 3, total 31), 2021, Nanjing Normal University, <a href="https://wenbohuang1002X.github.io/papers/2021outstanding.pdf">Certificate</a>.


<!-- #### <a href="#top" class="btn-xs btn-primary">Go Back to Top</a> -->

<!-- ### **Research Partners (Partial)**
<div style="clear:both"></div> 每六个人后便需要加这句
#### **Supervisors**
<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/huixue.jpg"/>
<p style="text-align: center;"> <a href="http://palm.seu.edu.cn/hxue/" target="_blank">Hui Xue</a><br>Ph.D Supervisor</p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/leizhang.jpg"/>
<p style="text-align: center;"> <a href="http://leizhangnjnu.github.io" target="_blank">Lei Zhang</a><br>Master Supervisor</p>
</div>

<div style="clear:both"></div>

#### **Instructors**
<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/junhe.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://sites.google.com/site/hejunzz/" target="_blank">Jun He</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/haowu.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://www.researchgate.net/profile/Hao-Wu-19" target="_blank">Hao Wu</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/fuhongmin.jpg"/>
<p style="text-align: center;"> <a href="https://www.researchgate.net/profile/Fuhong-Min">Fuhong Min</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/aiguosong.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://scholar.google.com/citations?hl=zh-CN&user=RjQ5TrEAAAAJ" target="_blank">Aiguo Song</a></p>
</div>

<div style="clear:both"></div>

#### **Friends**

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/qiteng.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://github.com/tengqi159" target="_blank">Qi Teng</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/kunwang.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://github.com/KennCoder7" target="_blank">Kun Wang</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/zhenyuwang.jpg"/>
<p style="text-align: center;"> <a href="https://github.com/Divine-w">Zhenyu Wang</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/yintang.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://yinntag.github.io/" target="_blank">Yin Tang</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/tianyiliu.jpg"/>
<p style="text-align: center;"> <a href=" ">Tianyi Liu</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/wenbingao.jpg"/>
<p style="text-align: center;"> <a href="https://scholar.google.com/citations?user=ggPvJNgAAAAJ&hl=zh-CN">Wenbin Gao</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/xingwang.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://chauncey-wang.github.io/" target="_blank">Xing Wang</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/chaoleihan1.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://chaolei98.github.io/" target="_blank">Chaolei Han</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/shuoyuanwang.jpg" target="_blank"/>
<p style="text-align: center;"> <a href="https://claydon-wang.github.io/" target="_blank">Shuoyuan Wang</a></p>
</div>

<div style="width: 14%; float: left; min-width: 9em;">
<img loading="lazy" width="98%" height="98%" style="border-radius: 10%;" src="../images/partnet/zhixiangwang.jpg"/>
<p style="text-align: center;"> <a href="https://claydon-wang.github.io/">Zhixiang Wang</a></p>
</div>

<div style="clear:both"></div> -->
<!-- 每六个人后便需要加这句

<!-- #### <a href="#top" class="btn-xs btn-primary">Go Back to Top</a> -->

<a href="#" class="toTop"><br><br><br><br>Go Back to Top</a>