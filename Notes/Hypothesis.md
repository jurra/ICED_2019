# Hypothesis to verify with literature:
### Keywords: continuous development, componentization and modularity, integration (reflected in architecture, organization of teams)
1. There is a transfer going on of mainstream software design culture to physical products, and design.
1.1 Just in time is part of a modern phenonmenon of continuous  improvement of productivity.[ ], [ ], [ ]
1.2. ** The new revolution has been the addition of open source in these context of productivity, where productivity is not anymore an exclusive concern of industries, and enterprise led innovations. This is the innovation coming from the public domain and disrupting the traditional industrial model (B2B and B2C lead based innovations)** (This is the singularity of the phenonmenon)[ ], [ ], [ ]
> Hay que reconocer que ha habido un proceso de cooptacion

2. The current composition of software culture includes all aspects of activities such as division of labor, tools, organization and management practices, a pattern of division of labor.[ ], [ ], [ ]
2.1. These consolidation within the domain can be traced back to Toyota.[7]
2.2. The design culture, has played a particular role in shaping this culture with regard to user centeredness, interaction design, etc.[33], [],[],
2.3. These culture is of an integrated and collaborative kind by design (organization in terms of micro and macro management).


## Empirical domain: What are the observables?
- Artifacts: Contributing guidelines,
- Releases?


## My observations conclusions, from empirical evidence:
1. With regard to contributing guidelines. The tools differ, but they all essentially depend upon peer review by project owners, in RepRap or ther (For software the basis is git).
2. The concept of subcultures, each subculture with specific contributing guidelines. The hacker subculture, of open source free software, etc.
3. The key is peer-review work. And then there is peer review in a context of open collaboration, vs peer review in the context of enterprise. The pattern of collaboration differs in gitlab, vs git, because git is not an enterprise while gitlab is?
4. The just in time notion, is still being developed in software as continuous delivery, with its own particularities. Similarity between devops and just in time.
5. Another discovery, the cultural transfer taking place: the open source software subculture, vs  the devops culture, and just in time; collaboration in different manners.
6. Another angle at which we can see things with regard to open source is at "design", what is designed? by products build with the platform, software design or improvement. How can design be analyzed with this regard? Design for replication, design for contribution, design for kits. In this regard Arduino, for instance looks like an onion, with layered design activities.
7. Arduino is a (meso activity system), like all the rest of examples like RepRap, etc.
8. Open Source is a basis for collaboration, but it does not imply in itself that is "wide open and collaboratio is wide open".
9. Open Source Product/Projects vary in their activity structure as well as the way in which people or organizations use them. Therefore it is a multidimensional object, meaning that there are different motives, around the outcome (The open source product).
10. A key differentiation to pick up the projects to analyze is the level of participation (Need to put the level of participation as part of the review).
11. We can identify different level of maturity in open source (from very simple p2p interaction, to more complex integrated efforts), but overally at the macro level the fact that all these small efforts add up already changes the perspective on how to design, research and develop. Open exchange, direct authorships facilitate p2p exchange. Also the fact that the process is more transparent.
  - For example in [37] people  

12. Regardless of the fact that hardware design, and also visual design can work with git, with some limitations in comparison to code. It is still possible and the best version control available that can be used for 3D files.
14. Talk about git in particular, as the tool for version control
15. Found differences between open source software development and open hardware developments
>We find that its structure differs substantially from that of open-source software, emphasizing multiple alternatives from small- scale partnerships rather than centralized public processes.

[37] About differences between open hardware and open software
> In contrast with open-source software, where development tends to be done publicly with anyone able to contribute, much of the development of the Arduino variants was done privately by select collaborators.

[37] About usage of version control
> None of the projects make regular public use of a software version control system (like Subversion or Git), although the Sanguino used an online version control system to publish the finished design files. The design files for the Arduino variants tended to be published, if at all, only when they were finished and the board had been produced. As a result, the boards have very few public versions (to date). Three of the variations (the Boarduino, Illuminato Genesis, and Seeeduino Mega) appear to have had only a single public release and all but the Freeduino have had five or fewer. Interestingly, though, over half of the variations were themselves the basis for further variations, typically by the same developer or manufacturer.

[37] Characteristics of open source hardware Evolution
> These variations on the Arduino circuit board present a very different portrait of open-source collaboration than that seen in most open-source software projects. It is an ecosystem of many small groups or companies providing alternative offerings within a product space. Individual products undergo few iterations; instead, their designs are used as the basis for new alternative variations. In this model, open-source collaboration means increasing the number of choices offered to users rather than improving the functionality of a single, central option. This

This also happens with reprap, instead of improving one single concept, a lot of variation takes place.

[37] Difficulties about version control:
> While existing version control systems can be used for hardware designs, they simply store subsequent versions of a file without providing mechanisms for understanding the differences between them.

This points to the need of having more advanced version control systems for hardware design. We need a git for hardware, CAD and more.

[37] Conclusions about difficulties with open hardware collaboration 
> In examining these variations on the Arduino Duemilanove, we’ve sketched a model of collaboration in open-source hardware. It is very different from that typically seen in open-source software, involving multiple small-scale collaborations rather than many people working on a single project. We identified three possible reasons for this structure: the complication of sharing components, the investment required for prototyping, and the lack of mature software tools for collaboration. Still, despite these challenges, we think this case study shows some of the exciting and evolving possibilities of open-source hardware collaboration.


[35] About collaboration and decision making
> Improve internal collaboration within one’s own organization.
Effective open source is all about removing collaboration barriers. Often people think
of those barriers as occurring at entity boundaries, but large organizations usually have
a variety of internal boundaries as well. Adopting structures that encourage inter-team
collaboration tends to increase it regardless of whether the two teams reside at different
companies or simply different business units.


[2] On why using activity centered design for the methods section
> Context-based design builds on human-centered design by positioning the interactions between users and mediating tools within the motives, community, rules, history, and culture of those users.

[2] Marco teorico para introducir los metodos:
> As indicated by Engeström’s (1999a) model, an activity system consists
of people, artifacts, an object or motive, sociocultural rules, and roles (Kaptelinin, Nardi, & Macaulav, 1999). Kari Kuutti (1996, p. 27) has characterized activity as “a form of doing directed to an object.”

> The interaction between actors in an activity system is mediated by the
object of activity, by language and tools, by a division of labor, by conven- tions, and by social rules. P



[4] On characterizing activities
> a more detailed level, it also requires that designed artifacts ef- fectively support the combined actions by which these purposes are advanced. Third, a well-designed artifact takes into account the community of participants, their roles, and the rules regulating their activity

>In particular, activities take place in and over time, within a particular physical and so- cial setting, and are performed in characteristic manners, styles, or patterns.



From the contributing guidelines of the Git project
> GitHub is designed around a particular collaboration workflow, centered on Pull Requests. This flow works whether you’re collaborating with a tightly-knit team in a single shared repository, or a globally-distributed company or network of strangers contributing to a project through dozens of forks. It is centered on the Topic Branches workflow covered in Git Branching.

[Example of improvement in reprap development threads](https://reprap.org/forum/read.php?2,628638)

# Put here topics about literature review, with regard to peer production
HCI Interaction Design, UX, CX

Engestrom on complexity of activity systems
> First, different activity systems become gradually larger, more voluminous, and denser in their internal communication with a growing number of people.[3]

This is particularly the case for peer to peer production, where more people participate and therefore need to coordinate and plan their approach. As the volume of participants grow in an activity, the need for new tools, and rules become more evident.

>Second, different activity systems, and people within them, become increasingly interdependent, forming ever more complex networks and hierarchies of interaction. Third, this interdependence of activity systems is increasingly penetrated and saturated by the basic socioeconomic laws and by corresponding contradictions of the given society [3]

> Expansion is qualitative transformation and reorganization of the object.[3]

> Elucidating the conflicts among activities and among competing goals are considered to be essential to understanding how activity takes place and evolves.[4]

For instance contributing guidelines and codes of conduct are used to facilitate conflict resolution, and decision making.

> Activity theory is a theory of object-driven activity. Objects are concerns, they are generators and foci of attention, motivation, effort and meaning. Through their activities people constantly change and create new objects. The new objects are often not intentional products of a single activity but unintended consequences of multiple activities.
The [5]

> Runaway objects have the potential to escalate and expand up to a global scale of influence. They are objects that are poorly under anybody’s control and have far-reaching, unexpected effects. Such objects are often monsters:....
Runaway objects are contested objects that generate opposition and controversy. They can also be powerfully emancipatory objects that open up radically new possibilities of development and well-being. The Linux operating system is a well-known example. [5]

Linux and Git are examples of Runaway objects. Git is actually a tool, a very complex artifact that mediates the activity of software development, version control and maintanance, considering the big scale and complexity of this kind of activity. Github, y eventualmente gitlab son otro ejemplo.



> The object must yield useful intermediate products, yet remain an incomplete project. The object must be visible, accessible and cumulable - allowing participants to return time and again. There must be effective feedback from and exchange among the participants acting on the object.[5]

Esto esta bien para platform design, y para los conceptos que estoy desarrollando.

[9] Influencia de lean thinking que viene de toyota
> For example, lean thinking can be traced back to the Toyota
Production System in the 1950s with its focus on the reduction
and elimination of waste
