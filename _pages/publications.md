---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<table>
		<tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Kanani, P. "Resource-bounded Information Acquisition and Learning", PhD Thesis 2012, University of Massachusetts Amherst &nbsp <a href="publications/FinalThesis.pdf">  pdf </a> &nbsp BibTex   
		  </p></td>
         </tr> 
		
		<tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Kanani, P. and McCallum, A. "Selecting Actions for Resource-bounded Information Extraction using Reinforcement Learning", In Proceedings WSDM 2012, Seattle, WA.  &nbsp <a href="publications/wsdm332-kanani.pdf">  pdf </a> &nbsp BibTex   
		  </p></td>
         </tr> 
		 
		 <tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Kanani, P. and McCallum, A. "Learning to Select Actions for Resource-bounded Information Extraction". UMass TechReport UM-CS-2011-042, 2011. &nbsp <a href="publications/Kanani2011TechResport.pdf">  pdf </a> &nbsp BibTex  
		  </p></td>
         </tr> 
		
		<tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Svore, K., Kanani, P., and Khan, N., "How good is a span of terms? Exploiting proximity to improve web retrieval", Proceedings of the 33rd ACM SIGIR'10, pp. 154-161. &nbsp <a href="publications/fp728-svore.pdf">  pdf </a> &nbsp <a href="publications/sigir2010.bib"> BibTex </a>  
		  </p></td>
         </tr> 
		
		 <tr>
          <td class="bodyText" colspan="2"><p class="style1">
            Kanani, P., McCallum, A. and Hu, S., "Resource-bounded Information Extraction: Acquiring Missing Feature Values On Demand", Proceedings of the 14th PAKDD, Hyderabad, India, June 21-24, 2010. <b>(Winner of Best Student Paper Runner Up Award)</b>. Also appeared as a poster in NESCAI 2010. &nbsp <a href="publications/pakdd2010kanani.pdf">  pdf </a> &nbsp <a href="publications/pakdd2010kanani.bib"> BibTex </a>  
		  </p></td>
         </tr> 
		 
         <tr>
          <td class="bodyText" colspan="2"><p class="style1">
         Kanani, P., McCallum, A., and Sitaraman, R., âTowards Theoretical Bounds for Resource-bounded Information Gathering for Correlation Clusteringâ, UMass TechReport UM-CS-2009-027 <a href="publications/synthesis_pallika.pdf">  pdf </a> &nbsp <a href="publications/tr09_rbig.bib"> BibTex </a>  
          </p></td>
         </tr> 
        
     
         <tr>
          <td class="bodyText" colspan="2"><p class="style1">
          Kanani, P. and Melville, P., "Prediction-time Active Feature-value Acquisition for Customer Targeting", NIPS 2008 Workshop on Cost Sensitive Learning.  &nbsp <a href="publications/afa-nips08.pdf"> pdf </a>  &nbsp <a href="publications/afa-nips08.bib"> BibTex </a>
         </p></td>
         </tr> 
        
        <tr>
          <td class="bodyText" colspan="2"><p class="style1">
         Kanani, P. and McCallum, A., "Efficient Strategies for Improving Partitioning-Based Author Coreference by Incorporating Web Pages as Graph Nodes," Proceedings of the Workshop on Information Integration on the Web (IIWEB 07), pp. 38-43. Also appeared as a poster in NESCAI 2007. &nbsp <a href="publications/aaai07_rbig.pdf"> pdf </a>  &nbsp <a href="publications/aaai07_rbig.bib"> BibTex </a> 
         </p></td>
         </tr>
         
         <tr>
          <td class="bodyText" colspan="2"><p class="style1">
          Culotta, A.,  Kanani, P.,  Hall, R.,  Wick, M. and McCallum, A., "Author Disambiguation using Error-driven Machine Learning with a Ranking Loss Function," a workshop at the Sixth International Workshop on Information Integration on the Web (IIWeb-07), Vancouver, Canada.  &nbsp <a href="publications/aaai07_author.pdf">  pdf </a> &nbsp <a href="publications/aaai07_rbig.bib"> BibTex </a>
         </p></td>
         </tr>
         
         <tr>
          <td class="bodyText" colspan="2"><p class="style1">
         Kanani, P. and McCallum, A., "Resource-bounded Information Gathering for Correlation Clustering," in the Proceedings of Computational Learning Theory 07, Open Problems Track, COLT 2007, LNAI 4539, pp. 625-627, 2007. &nbsp <a href="publications/colt07_rbig.pdf">  pdf </a> &nbsp <a href="publications/colt07_rbig.bib"> BibTex </a>  
         </p></td>
         </tr>
         
         <tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Kanani, P.,  McCallum, A. and Pal, C., "Improving Author Coreference by Resource-bounded Information Gathering from the Web," in the Proceedings of the International Joint Conference on Artificial Intelligence (IJCAI 07), pp. 429-434, 2007.  &nbsp <a href="publications/ijcai07_rbig.pdf"> pdf </a> &nbsp <a href="publications/ijcai07_rbig.bib">  BibTex </a>   
         </p></td>
         </tr>
        
		<tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Young, J.W., Webster, T., Adolph, K. E., Robinson, S. R., & Kanani, P. "The effects of sampling frequency on developmental trajectories". International Society for Developmental Psychobiology, New Orleans, LA, 2003
		  </p></td>
         </tr> 
		 
		 <tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Biu, O., Young, J. W., Pethkongkathon, J., Kanani, P., & Adolph, K. E. "A microgenetic analysis of the trajectory of motor development". Society for Research in Child Development, Tampa, FL, 2003
		  </p></td>
         </tr> 
		 
		 <tr>
          <td class="bodyText" colspan="2"><p class="style1">
           Young, J.W., Biu, O., Pethkongkathon, J., Kanani, P., & Adolph, K.E., "Continuity and discontinuity in motor skill acquisition". International Society for Developmental Psychobiology, Orlando, FL, 2002
		  </p></td>
         </tr> 
         </table>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
