__Henry Senyondo, Annual self self-assessment (Spring 2016)__

__1. We recommend including the following components:__


### Work Done

    release of retriever 1.8
    
##### Main elements

    Test Coverage 
    Documentation 
    Depsy for Science/Research Audience metric measure 
    Improve Testing and cross platform support
    
###### upgrades

    Pytest platform
    Travis container-based infrastructure
    
###### workshops

    1) Software carpentry instructor's workshop
    2) Software carpentry UF workshop (r)   
    
> * Remarks: The first workshop was great. I need some improvements in some areas. Excited for the next workshop

###### Upcoming Workshops

    Moore DDD Puerto Rico from May 31 - June 2. 
    NEON's Work with Data Institute working with heterogeneous spatio-temporal data June 19-25, 2016 
    
### Work to Do:

##### Retreiver

    Over 60 issues on the retriever to be covered.
    
###### Core Parts:

    Transition to Python 3.
    Removing Gui and Re-brand as Data Retriever.    

###### Testing 

    Expand unit testing and add code coverage checks.
    cross-tab testing and cross-tab primary key creation.
    Skipping fields(Primary Key)
    Better testing appraoch
    Scripts testing for all datasets(fast approach)
    Check MySQL and Postgres credential files
    Add windows appveyor, Travis CI for iOS tests
    
###### features:

    Json Engine
    XML Engine
    HDF5 Engine
    Python Interface
    Import Spacial Data  
    
##### Weaver

    release of Weaver 1.0
    
##### Google summer Code:

    Mentoring (shift to python 3 and Json script)
    
### Completing this phase

Development:

    
##### Retriever (By the end of Summer)

    For the issues, I have gone ahead to divide them in two ways; considering the Milestones and the relationship with one another.
    For example, considering the section above of testing, you find that the issue "Expand unit testing" will involve taking care of the cross-tab, making sure that primary keys are set right too. 
    For the retriever, I believe covering the two sections (Testing and Features above), will reduce the number of issues tremendously    
    
    
##### Weaver( By End of April): 

    Main part of weaver 1.0 is to be able to integrate files from different sources and support spacial integration. 
    Currently, we are in the development phase with a prototype working using sqlalchemy to integrate datasets.
    We are using a configuration file for the protocol of integration. 
    Aditionally we have added Raster spacial data and we are under Tests for the vector datasets. 
    Once this is done, we will have our first tool ready for merging with spacial datasets that can be handled by gdal. 
    I believe by the end of April the first version of the tool will be ready.
    
  
###### Current development Issues with the Weaver project

    Most of platform issues that the retriever has had or is having can be directly linked with the weaver. 
    I have been trying to solve some of these issues in parallel or consider them when developing for the weaver. 
    For example, cross-platform testing with travis and appveyor.

* __What are your long-term career plans?__
        
I do believe that I am in the right career path currently.
I have not directly contributed much to my long-term career endevours and this is because the first few months have been a learning process. However I get to see code everyday which is also a contributuion to my career.
I plan to expand these courses/workshop kind of services to my former universities and Africa. I have always tried to do this in Africa but I have always had obstacles. This time, I am actually trying to ask some of the universities in africa to get involved in workshops like SWC, DC and ML workshops. So being involved in these Carpentries is very good as part of my long term goal.
On the side, I also want to go back and attend those lecture series on coursera or any new platforms atleast one every year or 6 months.


* __Given your long-term plans, what do you think you need to do to be successful?__ 

My plan was simple, first get the tools(retriever, weaver) to a stable state and then you can get involded in more plans and projects. 

* __What did you accomplish this year towards accomplishing your goals?__

Luckily I got a chance to be part of the certified instructors at Software Carpentry and conducted a Software Carpentry workshop.

* __What are your plans for next year for working towards your goals? (Be as specific as you can be. Are there particular projects you plan to start/finish? Is there specific training or experiences you think you need to succeed in reaching your goals?)__

    Currently I am not applying for any jobs and probably next year.
    Next year is a year for me. (Assuming next year Starting from May)
    April will be to finish up the first version of the Weaver


###### Goals for the Retriever:

    We have 48 datasets, Personally I do feel we need to increase on the datasets covered. I am targeting next year's Dataset to increase so that we can have a big research impact. The theory I have is, if it is safe to say, we have over 2000 major/main 4-year institutions dealing with data in USA/World, how can we scale the tool's use over at least 100 major centers/institutions. 

###### Ideas:

    Teaming up with large data centers and Organizations. Remarks: we have already done much of this (Neon, Moore Foundation, Software Carpentry and Data carpentr).
    We can also include sample examples using the tools in the Carpentry workshops.
    Increase the number of Datasets that can be handled by the tool so that many scientists can make use of the tool.
    Remarks: This may require good and thorough research for the most used datasets or datasets from major research Centers.

###### Goals for the Weaver:

    Currently the main goal for the Weaver is to get it going before we can come up with concrete goals.
    However, we do believe once we can handle spacial data, we can look in the directions like remote sensing and many more

 __2.  It should be written down. This gives you a record next year of what you thought you needed to be doing so you can compare what you did with what you wanted to do.__
 
Done

__3. Share it with us. This is totally voluntary, but we know a little bit about succeeding in academia and we know a lot of people who work in other areas of science (and software engineering). Our goal is to help you be successful in whatever career path you choose. Knowing what you want to do, what you think you need in order to do it, and what you want to accomplish helps us advise you better during your weekly meetings.__

Done

Also, a note for more permanent staff: we think you're awesome, and we'd love for you to stick around forever, but we know that you may have bigger plans, and you know that these kinds of positions are always dependent on sufficient funding being maintained in the labs. We want you to get where you want to go, so you shouldn't worry about sharing goals with us that involve you leaving at some point. Of course it's totally understandable if you don't want to tell us about this (or if you never want to leave), but just know that we'll be supportive of whatever you're trying to do


