# GIStory Issue 15 | Li Xiaojiang: Data Mapping Cities, Intelligence Reshaping Space

## Guest Introduction

Dr. Li Xiaojiang is currently an Assistant Professor in the Department of City and Regional Planning at the University of Pennsylvania, and also co-founder of Biometeors. He previously served as an Assistant Professor at Temple University and conducted postdoctoral research at the **MIT Senseable City Lab**. His cutting-edge explorations and academic contributions in urban studies and geospatial analysis have not only advanced related theories and methods but have also gained international recognition. In 2021, he was selected by *Geospatial World Magazine* as one of the global **"50 Rising Stars"** and received the Global Young Scientist Award.

Professor Li's research focuses on **urban science, spatial data science, and data-driven urban environmental modeling**. He is among the earliest scholars to combine machine learning with Google Street View data for urban environment research, primarily by training deep learning models to automatically identify and extract urban elements such as vegetation and building morphology from street view images, assessing street-level green visibility and urban spatial quality. He led the development of the **Treepedia** project, mapping street greenery for cities worldwide and promoting the quantitative analysis and visualization of urban green spaces. Additionally, he utilizes cutting-edge technologies such as **Geospatial Artificial Intelligence (GeoAI)**, urban analytics, and urban microclimate modeling to deeply study the impacts of extreme heat on pedestrians and different communities, providing scientific evidence for urban climate adaptation and sustainable development.

In this issue's interview, GIStory spoke with Professor Li Xiaojiang, conducting in-depth discussions around his academic journey, research methods, technological innovation, and interdisciplinary exploration. Professor Li shared how he gradually shifted from remote sensing data research to street view image analysis, and how he combines artificial intelligence, urban microclimate modeling, and other frontier technologies to optimize urban environment analysis in his data-driven research process. The interview also explored the sources of research inspiration, the selection of research directions, and how to translate theoretical research into practical applications to promote urban sustainable development. Let us step into this deep dialogue about data and cities.

**Personal Academic Homepage:** [https://www.design.upenn.edu/people/xiaojiang-li](https://www.design.upenn.edu/people/xiaojiang-li)

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/1.png"></p>


## 01 The Shift in Research Perspective: From Remote Sensing to Street View

Professor Li Xiaojiang's academic journey is filled with exploration and interdisciplinary exchange. He completed his undergraduate studies at **Henan University**, majoring in environmental science. Influenced by geography courses, he developed a strong interest in spatial data such as cartography and remote sensing imagery. During his studies, he actively participated in various academic forums and lectures, engaging with methods and theories from different disciplines, and broadly explored fields including mathematical modeling, remote sensing analysis, computer programming, and spatial data processing. These interdisciplinary learning experiences laid a solid foundation for his later research.

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/2.png"></p>

&gt; **Figure 1: Photo of Professor Li (second from right) during his student years**

At the master's level, Professor Li participated in **high-resolution remote sensing image classification research** at the Chinese Academy of Sciences Institute of Remote Sensing and Digital Earth (AIRCAS), focusing on accurately identifying different land cover categories from high-resolution remote sensing images (HRS). During this process, he had the opportunity to participate in a project collaborating with a Hungarian team, which involved multiple types of high-resolution aerial remote sensing data, including high-resolution aerial imagery, hyperspectral remote sensing, and LiDAR data. At that time, the application of these data types in China was still in its early stages, and this experience not only allowed him to master core technologies in remote sensing image processing but also made him deeply recognize the impact of data quality, classification methods, and algorithm optimization on final results. In this project, he explored classification methods based on **Support Vector Machines (SVM)** and **Object-Based Image Analysis (OBIA)** techniques, and optimized the accuracy of urban land use classification.

In modern urban research, remote sensing technology has long provided powerful data support for macro-scale environmental monitoring. When he began his doctoral research in 2013, Professor Li gradually realized the limitations of traditional remote sensing data—relying solely on remote sensing imagery made it difficult to comprehensively reflect the micro-characteristics of urban environments. Although remote sensing imagery can provide a broad perspective of the urban surface, it struggles to reflect more microscopic **"human-centered perspectives."** For example, remote sensing data can measure urban green coverage rates but cannot describe pedestrians' real experiences on streets—that is, the actual green visibility they see (Li et al., 2015). This prompted him to consider: could street view data be combined to provide urban environment analysis methods more aligned with actual human experience?

&gt; *"Remote sensing imagery can tell us the vegetation coverage rate of the surface, but cannot describe the distribution of street trees from the pedestrian's perspective. I began to wonder, can we use street view data to provide a more 'human-centered' urban environment analysis method?"*

Therefore, he decided to explore how to use street view imagery for urban environment research. He developed a set of **street view data-based urban greening analysis methods**, using Python scripts to automatically call the Google Street View API, extracting and analyzing information such as vegetation and building morphology from street view images (Li et al., 2015). In this process, he drew on his experience in high-resolution remote sensing data processing from his master's period, exploring how to accurately identify green vegetation from RGB-band street view images and optimizing the accuracy of greening rate calculations through computer vision algorithms (Li, Wang, & Zhang, 2017).

&gt; *"At that time, this technology was not yet mature. How to efficiently acquire and analyze street view data was a great challenge. I tried many different algorithms to improve analysis accuracy and computational efficiency. These technical methods provided great help for my subsequent street view analysis, urban microclimate simulation, and other research, and also made me more determined to转向 this research direction. At the same time, I was fortunate to become one of the first scholars to use street view data to study urban environments."*

In the process of comparing remote sensing data and street view data, he found that although remote sensing imagery provided a macro perspective of the urban environment, it lacked detail capture at the street level. In contrast, street view data can precisely present the micro-characteristics of urban spaces, such as the density of street trees, building facades, and sidewalk widths (Li, Wang, & Zhang, 2017). This research not only broadened the application boundaries of remote sensing data but also provided new data support for urban planning and environmental assessment.

Professor Li's doctoral research laid an important foundation for his subsequent explorations in the field of urban environment and spatial analysis. During the research process, he gradually formed a **data-driven urban environment analysis methodology**, applying this concept to multiple research projects, including: **urban microclimate modeling, transportation, environmental equity assessment, and large-scale urban greening monitoring**.


## 02 Key Turning Points: From Doctoral Life to Academic Journey

### 2.1 Breaking Through the Probation Period: Street View Data and Sky View Factor Calculation

Professor Li Xiaojiang shared two key turning points he experienced during his transition from student to researcher. The first key turning point occurred during his master's stage, when his collaboration with the Hungarian team allowed him to gain early exposure to ultra-high-resolution multi-source spatial data and built a solid foundation in multi-source remote sensing data processing, laying a strong technical background for subsequent research. The second key turning point occurred during his PhD, when he applied for a postdoctoral position at the **MIT Senseable City Lab**. However, the lab typically prioritized postdoc applicants who had already had research experience in the lab, so he did not directly receive an offer but was given a **one-month probation period**. Near the end of the probation period, **Professor Carlo Ratti** assigned him a highly challenging research problem—how to combine street view data to calculate the urban **Sky View Factor (SVF)**. In fact, Carlo himself did not know whether it was feasible; he simply initiated this research because his research direction was in street view analysis. This research had a profound impact on Professor Li. Before this, he had never considered studying SVF through street view data.

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/3.png"></p>

&gt; **Figure 2: Professor Li at the MIT Senseable City Lab**

To find a solution, he deeply studied relevant papers by Professor Ratti and his team, and discovered that one of Professor Ratti's research directions during his PhD at Cambridge involved using **Digital Elevation Models (DEM)** to calculate SVF. Ratti et al. (2002) proposed an SVF calculation method based on urban 3D modeling, which used DEM data combined with satellite remote sensing imagery and 3D modeling data to accurately calculate SVF in urban environments (Ratti et al., 2002). Compared to traditional **Viewshed Analysis** methods, this new method significantly improved both computational efficiency and adaptability to complex terrain (Ratti et al., 2003).

This discovery made Professor Li realize that previous SVF calculation methods mainly relied on fixed-perspective data. For example, **Google Street View (GSV)** images mostly used horizontal viewing angles, and therefore could not accurately measure **sky openness**. To solve this problem, he proposed a new calculation method: using **GSV panoramic imagery** to calculate the relationship between **street enclosure** and SVF, and combining it with the **Building Height Model (BHM)** for comparison, to more precisely assess the impact of urban greening on solar radiation (Li, Ratti, & Seiferling, 2018). This method used GSV street view imagery to measure the degree to which SVF is obscured by trees. Compared to traditional methods based on satellite imagery or 3D modeling, this method can more accurately reflect the contribution of street-level trees to shading (Li, Ratti, & Seiferling, 2018).

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/4.png"></p>

&gt; **Figure 3: Schematic diagram of converting GSV cylindrical projection to azimuthal projection (fisheye imagery)**

Traditional SVF calculation methods mostly relied on **cylindrical projection** or **3D urban modeling**, but through Google Street View panoramic imagery, one can directly measure the degree of SVF reduction from the street level without relying on simulation, and compare it with building occlusion effects. This method effectively improved the accuracy of SVF calculation and provided important data support for urban greening optimization and microclimate regulation strategies (Li, Ratti, & Seiferling, 2018).


<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/5.png"></p>

&gt; **Figure 4: Comparison between SVF calculated from GSV panoramic images converted to fisheye imagery (GSV-based method) and traditional 3D model simulation**

&gt; *"At that time, I thought I could try this new method, but time was tight—I only had half a month of probation period. I wrote the algorithm within two weeks and completed a paper to submit to him. He directly said, 'This is the fastest-written paper I've ever seen. Come directly.'"*

This research was later published in *Landscape and Urban Planning*. This breakthrough not only earned him a formal postdoctoral position at the Senseable City Lab but also opened up an entirely new research direction for him—using high-resolution geospatial data to study urban microclimate, and promoting **data-driven urban thermal environment assessment methods**.

&gt; *"These two key turning points made me realize that research is not only about discovering problems, but also about the ability to respond quickly and find solutions."*

His doctoral research ultimately not only helped him secure a postdoctoral position but also garnered more attention for him in the fields of **urban spatial intelligence** and **environmental modeling**. His research results provided new data support for **urban sustainability** and were published in multiple international conferences and academic journals.

---

## 03 Research Innovation and Practical Application: From Theory to Urban Planning

Professor Li believes that the value of research depends not only on its novelty and innovation but more critically on whether it can bring **substantive improvements** and be **translated into real-world applications**. In the **Treepedia** project, he made street view data analysis of urban greening an important tool for urban planning (Cai et al., 2018).

&gt; *"Research cannot just remain at the theoretical level; it needs to truly land and serve practical problems."*

In the process of translating research from theory to practice, he emphasized that the practical application value of research exists inherently—for example, optimizing spatial data analysis, improving the precision of spatial phenomenon description, providing more accurate geographic information, and further proposing scientific evidence for urban environment improvement.

&gt; *"We need to make research truly serve society, promoting the popularization of data analysis tools so they can serve a broader population."*

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/6.png"></p>

&gt; **Figure 5: The Treepedia project in which Professor Li participated**

### 3.1 Urban Thermal Environment Analysis: Data Fusion and Optimization

For example, the ultra-high-resolution urban thermal environment analysis research he led (**HeatExpo**, [https://xiaojianggis.github.io/heatexpo/](https://xiaojianggis.github.io/heatexpo/)) precisely combines multiple data sources, including **aerial remote sensing imagery, LiDAR, and meteorological monitoring data**, to construct a more refined urban thermal environment analysis method (Li, 2021), capable of advancing urban thermal environment analysis to **1-meter spatial resolution** and **sub-hourly temporal resolution**. This research not only revealed the limitations of traditional research methods but also provided urban planners with more precise high-temperature impact assessment tools.

&gt; *"For example, thermal infrared remote sensing can only tell you the temperature of rooftops and treetops—in reality, no one lives on rooftops or treetops. Moreover, land surface temperature based on thermal infrared has very low spatial resolution, making it difficult to describe human thermal perception."*

Therefore, Professor Li adopted a **multi-source data fusion method with high spatial (1 meter) and high temporal (hourly) resolution** in thermal environment analysis, refining the spatiotemporal characterization of heat exposure. Furthermore, based on indicators extracted from street view images such as **street tree density, building occlusion degree, sidewalk width, and shadow coverage rate**, which collectively shape pedestrians' heat exposure situations at the street level, integrating these micro-environmental features into thermal environment simulation can better reflect key influencing factors such as thermal radiation and shading conditions in the space where the human body is located, thereby achieving a truly **"people-centered"** urban thermal environment assessment.

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/7.png"></p>

&gt; **Figure 6: Urban thermal environment analysis index (Li, 2021)**

### 3.2 Artificial Intelligence and Urban Environment Analysis

Professor Li's research has always kept pace with technological frontiers. He widely applies **Computer Vision (CV)**, **Deep Learning (DL)**, and **GPU parallel computing** in urban environment analysis. He pointed out that traditional physical models involve large computational loads, while artificial intelligence methods and GPU parallel computing can significantly improve computational efficiency. For example, in his **urban microclimate** research, based on multi-source high-resolution geographic data (including street view imagery, LiDAR, satellite remote sensing imagery, BHM, etc.), he simulated the **radiant temperature** actually felt by pedestrians, rather than relying solely on land surface temperature obtained from satellite remote sensing (Li et al., 2021).

However, Professor Li also mentioned that when promoting the application of new methods and tools, one often faces certain resistance. Many people are skeptical of new data or tools, believing they cannot meet practical needs. Therefore, he proposed a new perspective: describing the heat island effect by **simulating human perceptual experiences**, and exploring the potential impacts that new methods, new data, and new tools might bring.

&gt; *"Compared to technical problems, the challenge of dealing with people is greater. Scientific research must be able to provide significant improvements to truly motivate people to accept and apply new tools."*

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/8.png"></p>

&gt; **Figure 7: Professor Li participating in project discussions**

---

## 04 Research Inspiration: From Real-World Problems to Data-Driven Exploration

Professor Li discussed that research inspiration often stems from challenges and problems in the real world. He likes to conceive research directions by observing spatial phenomena in daily life, such as the impact of urban greening on pedestrian comfort, or urban thermal environments under extreme climate conditions.

&gt; *"I believe research should not be done in isolation behind closed doors, but should be closely connected to real-world problems."*

For Professor Li, much research inspiration comes from experiences in daily life—walking on streets, observing urban greening, building layouts, climate change, or even how pedestrians use space. These seemingly ordinary experiences often trigger new thinking and inspire potential research directions.

His research directions are also deeply inspired by data. He discussed that many research problems are not凭空 conceived but naturally emerge during the data analysis process. *"You will find that there is a lot of data that is very useful; it can tell you phenomena you were not originally aware of."* For example, when analyzing urban greening, he noticed that traditional green coverage rate indicators could not fully explain changes in urban thermal environments, which prompted him to further study the role of different types of greening in temperature regulation. Many breakthrough studies are born from these **data-driven discoveries**.

At the same time, Professor Li's high attention to new technologies has also profoundly influenced his research decisions. During the interview, he shared how he tried to use artificial intelligence and high-performance computing to optimize research methods. For example, when he first studied street view imagery, he encountered technical bottlenecks in data processing. With the development of deep learning and computer vision, he began applying more advanced algorithms to improve the accuracy and efficiency of data analysis. He emphasized that technological progress provides unprecedented tools for urban research, enabling researchers to explore urban environments at higher precision and larger scales. *"Today, we have more data sources and stronger computing capabilities, which allow us to propose research methods that were previously impossible to achieve."*

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/9.png"></p>

&gt; **Figure 8: Professor Li (third from left) participating in a seminar**

---

## 05 For Young Scholars: Interdisciplinary Perspective and Research Independence

Professor Li emphasized that **interdisciplinary collaboration** is crucial for driving innovation. He advised young scholars to not only delve deeply into their own research fields but also actively collaborate with experts from different disciplines to expand the vision and breadth of their research. Professor Li recalled that during his undergraduate and master's stages, he actively learned knowledge in multiple fields including **mathematical modeling, mathematical physics methods, finite element analysis, and numerical analysis**. Although these fields were not his research focus at the time, they played important roles in his later doctoral and postdoctoral stages.

He also mentioned that interdisciplinary methods often bring new research breakthroughs, so he suggested that young scholars draw on thinking and methods from different fields to conduct research.

Furthermore, Professor Li particularly emphasized the cultivation of **research independence**. He encouraged students to actively think during the research process, develop the ability to solve problems independently, rather than overly relying on advisors or existing research frameworks. He suggested that students cultivate an awareness of **active questioning** from the early stages of research, and continuously deepen their understanding of problems through experiments, data analysis, and literature reading.

Professor Li shared an experience from his master's period. At that time, he was very interested in a Greek team's research, so he proactively contacted them, expressed his research interest, and asked if they could share related code.

&gt; *"Actually, I didn't have too much expectation at the time, but in the end, they really replied to the email and shared the code."*

This experience made him realize that if interested in a problem, one should not be limited to resources around oneself but should **proactively contact everyone who can be contacted**. Therefore, he encouraged young scholars to broadly expand their **international academic networks**, actively participate in international conferences, academic seminars, and interdisciplinary collaborations to obtain the latest research dynamics and establish connections with the global academic community.

<p align="center"><img src="https://pub-b7009020d42e47bf93fb9f6c95502a87.r2.dev/gisphere_%E8%AE%BF%E8%B0%88/lxj/10.png"></p>

&gt; **Figure 9: Professor Li participating in an academic conference**


## 06 Message

At the end of the interview, Professor Li shared his core philosophy on research:

&gt; *"Interest is the best driving force."*

He encouraged young scholars to maintain curiosity on their research path and continuously try new research directions.

&gt; *"Finding a research direction you are truly interested in is not only the key to success in an academic career but also the greatest pleasure of research work."*

&gt; **Figure 10: Professor Li's daily life photo**

---

## 07 References

[1] Cai, B. Y., Li, X., Seiferling, I., & Ratti, C. (2018, July). Treepedia 2.0: applying deep learning for large-scale quantification of urban tree cover. In *2018 IEEE International Congress on Big Data (BigData Congress)* (pp. 49-56). IEEE.

[2] Li, X. (2021). Examining the spatial distribution and temporal change of the green view index in New York City using Google Street View images and deep learning. *Environment and Planning B: Urban Analytics and City Science*, 48(7), 2039-2054.

[3] Li, X., & Wang, G. (2021). GPU Accelerated Parallel Computing for Estimating Continuous Sky View Factor Map. *Research Square*.

[4] Li, X., Ratti, C., & Seiferling, I. (2017). Mapping urban landscapes along streets using Google Street View. In *Advances in Cartography and GIScience: Selections from the International Cartographic Conference 2017 28* (pp. 341-356). Springer International Publishing.

[5] Li, X., Zhang, C., Li, W., Ricard, R., Meng, Q., & Zhang, W. (2015). Assessing street-level urban greenery using Google Street View and a modified green view index. *Urban Forestry & Urban Greening*, 14(3), 675-685.

[6] Li, X., Yoshimura, Y., Tu, W., & Ratti, C. (2022). A pedestrian-level strategy to minimize outdoor sunlight exposure. *Artificial Intelligence, Machine Learning, and Optimization Tools for Smart Cities: Designing for Sustainability*, 123-134.

[7] Li, X., Zhang, C., Li, W., Ricard, R., Meng, Q., & Zhang, W. (2015). Assessing street-level urban greenery using Google Street View and a modified green view index. *Urban Forestry & Urban Greening*, 14(3), 675-685.

[8] Ratti, C., Di Sabatino, S., Britter, R., Brown, M., Caton, F., & Burian, S. (2002). Analysis of 3-D urban databases with respect to pollution dispersion for a number of European and American cities. *Water, Air and Soil Pollution: Focus*, 2, 459-469.

[9] Ratti, C., Raydan, D., & Steemers, K. (2003). Building form and environmental performance: archetypes, analysis and an arid climate. *Energy and Buildings*, 35(1), 49-59.