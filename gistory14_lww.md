# GIStory Issue 14 | Li Wenwen: A Wonderful Adventure from Computer Science to GeoAI

## Guest Introduction

Li Wenwen is a Professor and PhD Advisor at Arizona State University (ASU). Her current research interests primarily include **cyberinfrastructure**, **geographic big data**, **geospatial artificial intelligence (GeoAI)**, **geographic knowledge graphs**, and the application of these methods in natural feature detection, climate change, disaster relief, and other areas. She serves as Director of the ASU Cyberinfrastructure and Computational Intelligence Laboratory (CICI Lab), Research Director of the Spatial Analysis Research Center (SPARC), and former Chair of the Cyberinfrastructure Specialty Group of the American Association of Geographers (AAG). In 2023, she was elected as an **AAG Fellow** and a **UCGIS Fellow**. She has received the National Science Foundation (NSF) **Early CAREER Award**, the NSF **Mid-Career Advancement Award**, the AAG Spatial Analysis and Modeling Specialty Group **Emerging Scholar Award**, the ASU School of Geographical Sciences and Urban Planning **Distinguished Teaching Award**, the ASU **AI Innovation Award**, the Global Young Scientist Frontier Science and Technology Award, and others.

**Personal Academic Homepage:** [https://search.asu.edu/profile/1978357](https://search.asu.edu/profile/1978357)

<p align="center">
<img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lww/1.png">
</p>

## 01 From Computer Science to Geographic Information Science: Continuous Reinvention

Geographic Information Systems (GIS) are not merely a professional or technical branch, but a science capable of applying complex theoretical knowledge to fields closely connected with people's daily lives. Its broad range of applications has attracted numerous interdisciplinary talents, collectively driving the sustained prosperity of this field. Professor Li Wenwen is one such active explorer in this domain.

During her undergraduate studies in **Computer Science** at Beijing Normal University, Professor Li delved into cutting-edge computer technologies and gradually developed the idea of applying these technologies to other fields. After broadly exploring applied disciplines of computer science, she developed a strong interest in geographic information science. In her junior year, she successfully obtained **graduate school recommendation (保研)** qualifications and proactively contacted **Researcher Yang Chongjun** at the Chinese Academy of Sciences Institute of Remote Sensing Applications, a graduate advisor in the spatial computing direction. Upon their first meeting, Professor Li was moved by Yang's pragmatic and vibrant research spirit, and decided to begin her master's studies in this laboratory. Under Yang's guidance, Professor Li gradually stepped into the computer science research direction of geographic information science, including **GIS software system development, traffic navigation, and digital cities**, among other fields.

During her graduate studies, Professor Li became even more determined in her love for academic research. Recommended by Professor Yang Chongjun, she chose to pursue her PhD at **George Mason University**, studying under **Professor Yang Chaowei**. Through in-depth exploration during her graduate studies, Professor Li profoundly appreciated the broad application value of geographic information science and was attracted to research directions in **earth systems and climate change**. She aspired to apply big data-supported computer technology to this field. During her PhD, Professor Li primarily researched **ontology similarity**, **spatiotemporal data search**, and **distributed geospatial computing**, laying a solid foundation for her research path at the intersection of earth and environmental science with computer technology.

Before her PhD graduation, Professor Li faced two choices: remain at George Mason University or go to the **University of California, Santa Barbara (UCSB)** for postdoctoral research. Although staying at George Mason meant research continuity and more efficient paper output, driven by the desire to continuously challenge herself and explore new fields, Professor Li chose to listen to her inner voice. With the support of her advisor Professor Yang Chaowei, she decided to step out of her comfort zone and go to UCSB—meaning she would face the challenge of learning new domain knowledge.

At UCSB, Professor Li's postdoctoral research was based on her interests, focusing on **computational regionalization** in the field of urban social zoning [1]—for example, using spatial optimization algorithms to calculate continuous and more accessible compact zones. Although her postdoctoral research did not directly continue her PhD research content, this topic brought her new inspiration. During this stage, she gained new ways of thinking and the ability to rapidly transfer knowledge through interdisciplinary learning and exchange.

Through the accumulation of her academic journey, Professor Li believes that in the GIS field, computer technology gives us the ability to process geographic data, but the value of GIS far exceeds data processing. The sense of achievement from applying geographic information science theoretical knowledge to solve practical problems and create practical results became the driving force for Professor Li to continuously challenge and surpass herself, and also became the powerful support that propels her forward on her research path. Today, Professor Li and her team are dedicated to the interactive research of GIS, artificial intelligence, and big data, continuously innovating in practice.

<p align="center">
<img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lww/2.png">
</p>

&gt; **Figure 1: Group photo with professors and classmates as Professor Li's postdoctoral work at UCSB was coming to an end. Professor Li is on the far right. From left: Dr. Chen Yating, Professor Michael Goodchild, Professor Li Linna**


## 02 Embracing and Empowering Geographic Big Data

Based on her past experience in **ontology similarity** research (i.e., the similarity or correlation between different ontologies. An ontology is a formal expression of knowledge in a specific domain, while ontology similarity measures the degree of similarity in concepts, relationships, and overall organization between different ontology structures), Professor Li launched a **polar cyberinfrastructure** project in 2015. She led her team to successfully build the **Polar Hub** ([http://cici.lab.asu.edu/polarhub3/](http://cici.lab.asu.edu/polarhub3/)). This project aims to use distributed OGC web services, through intelligent sensing and discovery, to continuously expand the network to support scalable and sustainable data mining. Polar Hub not only realizes the visualization of geographic big data but also utilizes ontology and semantic reasoning technologies for query expansion and search recommendation. Since its establishment, Polar Hub has grown from an initial 200 data targets to the ability to query a total of **1.5 million data entries from over 150 countries**.

Through this project, Professor Li made significant progress in big data knowledge architecture. However, as research deepened, facing massive amounts of geographic knowledge, Professor Li realized that existing ontologies were difficult to effectively expand and augment within the scope of individual capabilities. Therefore, she believed that more advanced methods such as **Large Language Models (LLMs)** and **Knowledge Graphs** were needed to assist. In the GIS field, the development momentum of large language models is strong. They can process and understand natural language and generate high-quality text. Using large language models, one can automatically expand and refine ontologies and knowledge graphs, process large amounts of geographic data, and provide more intelligent and precise query and recommendation services. Based on this idea, Professor Li's team also began exploring how to apply large language models to GIS research.

When discussing **Geospatial Artificial Intelligence (GeoAI)**, Professor Li explained that the first step is to **exploratorily apply AI to the geography field**; the second step is to **improve AI's adaptability to geography by adjusting methods**, making customized adjustments according to different problems; the third step is to **feed research results back to computer science and other fields** [2].

Taking **computer vision** as an example, Professor Li shared some challenges faced when applying artificial intelligence (AI) to the geography field, particularly the issue of **spatial heterogeneity**. The existence of **spatial heterogeneity** significantly impacts the **spatial reproducibility** of AI models [3]. Professor Li explained that, for example, craters on the Martian surface experience varying degrees of erosion and coverage by snow, sand, and rock layers at different geographic locations, posing enormous challenges for monitoring craters across the entire Martian surface. When the Martian surface is divided into 10×10 degree grids, because effective imagery of craters near the equator is more abundant than near the poles, model accuracy is higher near the equator. In this experiment [4], Professor Li's team divided Martian latitudes into multiple datasets at 10-degree intervals and used three models to train on datasets at latitudes 0–10°, 60–70°, and -40° to -30°, respectively, then tested on all other 10-degree interval datasets. The results showed that model accuracy was higher in latitude regions near the training set, while accuracy gradually decreased in regions farther from the training set. Encouragingly, this experimental result demonstrated that when applying AI models to crater monitoring at different Martian latitudes, the spatial distribution of model prediction accuracy conformed to **Tobler's First Law of Geography**.

<p align="center">
<img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lww/3.png">
</p>

&gt; **Figure 2: Performance variance of GeoAI models across different grids [4]**


<p align="center">
<img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lww/4.png">
</p>

&gt; **Figure 3: Performance variance of GeoAI models across different latitudes for three training sets [4]**

Professor Li's research not only demonstrates the application potential of AI in the geography field but also shows that the spatial distribution of AI model accuracy exhibits characteristics of classic laws in geography. Faced with the rapid development of the GeoAI field, Professor Li expressed her excitement and expectations. She said:

&gt; *"Although AI's development is full of twists and turns and often faces many challenges, seeing colleagues continuously striving to promote and explore this field makes me feel incredibly excited and delighted."*

The tremendous potential of GeoAI has been tapped by many scholars, and Professor Li's passion and efforts have also made important contributions to the continuous progress of this field. In 2023, she collaborated with **Professor Gao Song** from the University of Wisconsin-Madison, **Professor Hu Yingjie** from the University at Buffalo, SUNY, and over 90 GeoAI scholars worldwide to co-author a book on geospatial artificial intelligence—**"Handbook of Geospatial Artificial Intelligence"**—becoming an important reference book summarizing and looking forward to GeoAI progress (Figure 4a). At the same time, in her latest article co-authored with multiple scholars in the field [5], she prospectively discussed important scientific questions in GeoAI, injecting new ideas and vitality into breakthroughs and development in this field. This article will also be published as an invited article in the *Journal of Spatial Information Science* this fall (Figure 4b).

<p align="center">
<img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lww/5.png">
</p>

&gt; **Figure 4: Latest GeoAI achievements summary (a) GeoAI Handbook published at the end of 2023 [5] (left) (b) Forthcoming invited article on "The Science of GeoAI" (right)**

---

## 03 Open Academic Discussion Paves the Way for Research

In conversations with Professor Li, **"exchange with professors"** became a hot topic. Whether as a graduate student or as a professor, she has always continuously explored and advanced through joint discussions with professors and classmates.

During her postdoctoral period, in a research project collaborating with **Professor Michael F. Goodchild** and **Professor Richard Church**, one part involved calculating **shape compactness**. Although many relevant calculation indices already existed, they still believed a better index needed to be proposed. To this end, they migrated a concept from the physics field—**the Moment of Inertia**—to the geography field and developed a new calculation index [1]. This process was full of challenges, but Professor Li resolutely tackled the difficulties. She not only invested a great deal of time learning physics theory but also proactively contacted physics professors at her university, engaging in in-depth exchanges with them, studying physics formulas, and discussing derivations with her professors. Professor Li recalled: *"When I went to Professor Goodchild to derive formulas, I watched with my own eyes as he picked up the formulas, and after quick calculations, easily unraveled the mystery, successfully deriving what I considered very complex mathematical formulas. Such a highly theoretical problem became effortless in his hands. This once again moved and impressed me: Professor Goodchild truly deserves to be a master-level presence in the GIScience field. Not only does he have a commanding grasp of the field's future, but he also has extremely profound insights into specific research problems."*

Professor Li greatly cherishes opportunities to discuss with different professors. She believes this process allows her to meet more excellent people, and learning and communicating with them is an exciting thing. Teachers and students with shared interests gather together, pursuing better results through joint discussion—this in itself is an anticipated process full of challenges and unknowns.

During her tenure as a professor, Professor Li also actively encourages students to communicate and discuss with professors. For example, she often goes to students' offices or connects through online meetings to have "intense" discussions with students about a problem. She and her students exchange solutions to problems from various angles, discuss the feasibility of methods, and anticipate multiple possible key points that need attention. Professor Li maintains a very open mindset regarding discussions with students. She believes that in the process of jointly exploring and assigning tasks with students, on one hand, the professor is training students' technical and expressive abilities; on the other hand, students are also反哺 (feeding back to) the professor, providing more specific knowledge supplementation and feedback on experimental results.

Professor Li emphasizes that it is everyone's **firm belief in research**, **inexhaustible innovative drive**, and **genuine curiosity from the heart** that enable us to discover problems in the collision and sublimation of ideas, in one new challenge after another, and to tackle difficulties and solve problems with strength and passion. Only through **mutual support, understanding, and joint efforts** between teachers and students can more outstanding research results be achieved. Professor Li's enthusiasm and curiosity are not only reflected in her exchanges with different professors and students but also inject infinite vitality and motivation into her research path. This love for exchange and exploration continuously inspires her to move forward, driving her to achieve greater accomplishments in scientific research.

<p align="center">
<img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lww/6.png">
</p>

&gt; **Figure 5: Offline group meeting discussion**

---

## 04 Be a Focused and Detail-Oriented Researcher

Behind the success of research projects lies the accumulation of countless small efforts. Every researcher has their own unique working style and characteristics, and the reason Professor Li has been able to harvest numerous scientific research achievements is inseparable from her excellent habits of **focus and attention to detail**.

During the interview, Professor Li shared her unique working style. She often concentrates deeply on researching a specific topic, rarely handling multiple tasks simultaneously (multi-tasking). She believes that switching back and forth between different work tasks not only requires mental shifting but also takes time to recall the progress and content of each task. This single-task working mode helps her complete tasks at hand better and more efficiently. At the same time, she stated that when time is limited, sustained focus can maintain interest in and deep thinking about research projects.

Furthermore, Professor Li pays great attention to **every detail in research**. She believes that the success of research projects stems from step-by-step accumulation and refinement—every detail is crucial, and these details determine the height of research. She consistently adheres to **high standards for details**, believing this is a respect for the hard work behind research achievements. For example, in managing references, Professor Li deeply understands that the accuracy and completeness of references represent respect and recognition for predecessors' research achievements. Therefore, although there are now many convenient reference management tools, after using these tools, she still carefully reviews the correctness of references to ensure accuracy.

Professor Li's work attitude and methods not only demonstrate her love and reverence for research but also set an example for young researchers. Her **focus, meticulousness, and persistent pursuit of research** are all valuable qualities worth learning from and emulating.


## 05 Message

At the end of the interview, Professor Li enthusiastically offered advice to every student: *"Everyone has their own era. Although you will encounter setbacks, sooner or later, this era that belongs to you will arrive."* As a senior who has weathered storms on the research path, Professor Li deeply understands the hardships and difficulties involved, and also deeply empathizes with the anxiety and concerns students experience on their journey of striving.

She shared that she too had experienced confusion and perplexity, but it was precisely those **persistent efforts and the spirit of not fearing setbacks** that allowed her to keep moving forward on her research path. She encourages students to **believe in themselves and hold firm to their convictions**, not to give up easily even when facing difficulties. Because when you look back, you will find that every attempt and effort before was paving the way for the future—they will eventually converge into your unique path of achievement.

Professor Li earnestly hopes that every student can **bravely face challenges and firmly walk their own research path**. Academia is like a marathon—initially, everyone sees who runs faster, but ultimately, what is compared is **who can persist longer and run farther**. She firmly believes that as long as you **maintain curiosity and persistent effort**, everyone will eventually usher in their own glorious era!


## 06 References

[1] Li, W., Goodchild, M. F., & Church, R. (2013). An efficient measure of compactness for two-dimensional shapes and its application in regionalization problems. *International Journal of Geographical Information Science*, 27(6), 1227-1250.

[2] Li, W., & Hsu, C. Y. (2022). GeoAI for large-scale image analysis and machine vision: Recent progress of artificial intelligence in geography. *ISPRS International Journal of Geo-Information*, 11(7), 385.

[3] Goodchild, M. F., & Li, W. (2021). Replication across space and time must be weak in the social and environmental sciences. *Proceedings of the National Academy of Sciences*, 118(35), e2015759118.

[4] Li, W., Hsu, C. Y., Wang, S., & Kedron, P. (2024). GeoAI Reproducibility and Replicability: a computational and spatial perspective. *Annals of the American Association of Geographers*, https://doi.org/10.1080/24694452.2024.2373787.

[5] Li, W., Arundel, S.T., Gao, S., Goodchild, M.F., Hu, Y., Wang, S., & Zipf, A. (2024). GeoAI for science and the science of GeoAI (invited article). *Journal of Spatial Information Sciences*. https://www.public.asu.edu/~wenwenl1/349.pdf