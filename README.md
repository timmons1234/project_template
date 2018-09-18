# Research Practicum 2018 – Research Plan

> * Group Name: Live Free or Data
> * Group participants names: Netterville, Sterkel
> * Project Title: Skill gap in Network/Security Engineering

## General Introduction
The fields of Network and Security engineering face are at a crossroads: highly skilled personnel are needed but there is a lack of personnel who possesses this depth of knowledge.

The lack of highly skilled personnel creates a problem at all levels from auditors, trainers and consultants to subject matter experts (SMEs). The issue at hand is not just in getting a few more people to the right skill level but to find a way to better educate the majority to raise the overall skill level in the fields of Network and Security Engineering. How can companies train newly hired employees (whether they have just graduated from college or are new to the fields) up to qualified levels were they can make a contribution? How can these new members be elevated to higher levels? What is a realistic time frame for this to occur?

The salary demands of highly skilled Network and Security Engineers also contributes to this skill gap. Those who have cultivated a high level of skill demand high costs for their services. This has lead companies to contract out these highly skilled Engineers when their expertise is needed. One downside to this method, and a contributor to the skill gap, is that these outside contractors provide little to no knowledge transfer when they perform their contracted duties (implementing a project, generating an audit). Even in situations where there is knowledge transfer from these experts, their lack of knowledge on what a company’s current employee's need make this knowledge transfer lacking at best. 

This creates an overall problem within the industry because companies do not hire experts long term. They expect existing employees to increase their skill and knowledge levels to fill the various niche roles within the technology architecture. But with the do more with less mentality so common in our industries, it means experts are constantly jumping between projects and engaging in spin up on little used skills. This leads to the need for a new training paradigm in these industries to use simulation based training techniques to help experts maintain their knowledge level and provide more customized training to those in companies who wish to improve their skills.



## Problem Statement
Network Engineering and Security engineering are difficult topics to teach and this problem is compounded by an aging curriculum and a lack of real world opportunities to put taught knowledge into practice. Potential Network and Security engineers enter the field with book knowledge that focus on idealized scenarios that are not backed up by real world experience. This is even further compounded because generally you need much more understanding than your area of expertise. For example, in the security engineering field one must know how and what to secure as well as have an understanding of the source material which needs to be secured. Knowledge of your own gear and of the protected material is needed. This leads to deep multi discipline understanding in a field where knowledge is already limited for new members.


## Motivation
Network and Security Engineering are two specialized areas facing skill gaps of their practitioners. Examining the problem has the potential to allow similarities to be drawn between network and security engineering and other markets which may allow training solutions that work in other markets to be applied to network and security training.  Examples of training paradigms that may be cross disciplinary are training the trainer, training the auditor, training management to better understand workloads, improving seasoning for green engineers.


## Proposed Solution. How do we propose to tackle this problem (that has been identified in the previous paragraphs, is interesting to the community, and has yet to be tackled by other researchers?
To tackle the problem of skill gap in Network and Security Engineering a three prong approach is proposed: Examining the problem, performing a literature review and proposing simulation based training to improve training in network and security engineering. 

The first step is to determine why there is a skill gap problem and what has exacerbated the issue. This will encompass reviewing how the industry has changed and how learning has evolved. It will also encompass examining areas for curriculum development and finding solutions for additional training.  A review of the literature will delve into what has been written about the skill gaps in network and security engineering, skill gaps in general between the expectations of employers and newly graduated employees, and what has been done in this area to utilize simulation to improve training.  Simulation based training is likely the fastest, most cost effective area for training. Network engineering focuses on repetition of core concepts tempered by problem solving. Simulation gives us the opportunity to create target areas for growth which promotes seasoning of engineers. Additionally, simulation creates safe environments where engineers can make mistakes and learn without affecting customers.

## Contributions
Collects existing research about the skill gap in network and security engineering
Examines the current state of these two fields
Examines methods for using off the shelf simulators to enhance curriculum

## The focus article:

> * Title:    Training network administrators in a game-like environment
> * Authors:  Engin Arslan, Murat Yuksel, Mehmet Hadi Gunes
> * Link:     https://www.ece.ucf.edu/~yuksem/my-papers/2015-jcna.pdf

The focus of this paper was the presentation of a novel way to train network administrations through a game like environment called the “Network Management Game (NMG)”.  The authors’ based this approach on game like environments used in the training of other disciplines such as flight simulators for training pilots.  The reason for the investigation into a new form of training for Network administrators was that traditional training methods, such as Cisco Certifications, take months and do not allow for training custom skills related to a particular network or configuration.  Another benefit of this type of training mentioned by the authors is that “simulations serve to compress and speed up the learning experience at a fraction of cost and risk”.  The paper describes the experimental setup that was used to test the knowledge transfer of the NMG.  During the testing phase the goal of the “game” was to “maximize the network's throughput by manipulation link weights” and this was tested in two different scenarios: Training without Mastery (players had a certain amount of time to complete level and once time ran out they were moved to the next) and Training with Mastery (players had to reach a certain score before they could move on).  Results showed that training on the system helped to improve a player’s ability to optimize a network through the manipulation of link weights. The authors' state that future research is needed to test different scenarios to see if they would also benefit from this kind of gamification."

The simulation based training method presented in the paper has the benefit of being a very useful product in bringing up the skill level of the industry.  The customization aspect could allow a company’s network to be mirrored and allow new employees that ability to train on it without affecting real operations.  


## Related Work
Whose job is it to train a new employee? What skill sets should a new employee have before entering the workplace?  What is the best way to train someone on the skills needed for Network and Security Engineering?  These questions arise due to the lack of highly skilled members in the Network and Security Engineering fields.


The first two questions in the above paragraph are the focus of many studies that try to determine what skillsets companies look for in recent graduates, what skills are taught at the university level and if there is disconnect between what companies want/expect of new graduates and what skills these new graduates show up with.  A common theme of these studies was that companies were valuing what Andres and Higson (2008) called “Soft Skills”, which are skills/knowledge not particular to a technical discipline over having specific technical knowledge.  Some of these soft skills included areas such as communication (both verbal and written), giving presentations, working in teams and leadership.  (Andrews and Higson, 2008; Markes, 2006, Nair, Paril and Mertova, 2009; Bridgstock 2009, Saunders and Zuzel, 2010).  In essence the discipline specific skills were not valued as high as students thought, rather companies preferred new hires who could be trained in house in certain technical skills (Saunders and Zuzel, 2010).


The literature seems to bring to light a mismatch between the skills companies expect future employees to have and the specific skills being taught at the university level.  The University of South Florida (USF) has made an effort to try to bridge this gap by applying a Systems Engineering approach to course creation which entail getting feedback from industry (Adithya et al, 2018).   If this shift were to take place (where non-technical skills are trained in place of specific technical skills) at a university setting, then what avenue would be the most appropriate to train those in the field of Network and Security Engineering.  Current training methods, beyond the basics taught at a university, essentially mirror the university setting.  These programs, such as that provided by Cisco, are structured with predefined lessons to teach basic generic technical skills over a period of months but nothing that is tailored to a particular company or application (Arslan et. Al, 2015).  As stated in the various studies companies need network administrators whose skills are tailored to their particular network setup and cybersecurity posture and who are highly skilled at maintaining the network and cybersecurity infrastructure.


New training methods are needed not only due to the ever changing aspect of the design and implementation of networks but for customizing a training program to a company’s specific architecture.  To facilitate this type of learning research is being done on game like and virtual training of networking concepts such as maximizing a network’s throughput, network routing, network configuration, load balancing and mobility (Ruiz Martinez et al, 2013, Arslan et al, 2015).  In one instance a game like environment is used, in another virtual networks were created (Ruiz Martinez et al, 2013, Arslan et al, 2015).  Gamification has been shown to enhance learning and motivation and “fosters active learning by providing them a bonus for every hindrance they overcome” (Adithya et al, 2018).  Another benefit of gamification and virtualization is that this training can be implemented to provide a stepped type of problem solving where difficultly can be gradually increased, certain scenarios can be developed as part of a training program and they can be implemented on a user’s computer for self-paced learning.  


## References 

APA Citation
> * Celikoglu, H. B., Haddad, J., Han, K., & Lebacque, J. P. (2018). Special Issue on Advances in Modeling, Simulation and Optimization of Dynamic Network Traffic. Transportation Research Part C: Emerging Technologies, 95, 442-444.
> * Joyce, D. L., Lahr, B. D., Maltais, S., Said, S. M., Stulak, J. M., Nuttall, G. A., & Joyce, L. D. (2018). Integration of simulation components enhances team training in cardiac surgery. The Journal of thoracic and cardiovascular surgery, 155(6), 2518-2524.
> * Adithya, P. C., Pandey, S., Caballero, J. A., Yürür, Ö., & Moreno, W. A. (2018). Systems Engineering Framework to Design a Laboratory Course: A Case Study.
> * Mason, G., Williams, G., & Cranmer, S. (2009). Employability skills initiatives in higher education: what effects do they have on graduate labour market outcomes?. Education Economics, 17(1), 1-30.
> * Boden, R., & Nedeva, M. (2010). Employing discourse: universities and graduate ‘employability’. Journal of Education Policy, 25(1), 37-54.
> * Andrews, J., & Higson, H. (2008). Graduate employability,‘soft skills’ versus ‘hard’business knowledge: A European study. Higher education in Europe, 33(4), 411-422.
> * Bridgstock, R. (2009). The graduate attributes we’ve overlooked: Enhancing graduate employability through career management skills. Higher Education Research & Development, 28(1), 31-44.
> * Nair, C. S., Patil, A., & Mertova, P. (2009). Re-engineering graduate skills–a case study. European journal of engineering education, 34(2), 131-139.
> * Saunders, V., & Zuzel, K. (2010). Evaluating employability skills: Employer and student perceptions. Bioscience education, 15(1), 1-15.
> * Mehrotra, S., Gandhi, A., & Sahoo, B. K. (2013). Estimating India’s Skill gap on realistic basis for 2022. Economic and Political Weekly, 48(13), 102-111.
> * Ramadi, E., Ramadi, S., & Nasr, K. (2016). Engineering graduates’ skill sets in the MENA region: a gap analysis of industry expectations and satisfaction. European Journal of Engineering Education, 41(1), 34-52.
> * Markes, I. (2006). A review of literature on employability skill needs in engineering. European Journal of Engineering Education, 31(6), 637-650.
