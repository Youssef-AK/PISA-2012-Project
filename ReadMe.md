# Pisa Dataset Exploration

### by Youssef Ahmed Khattab


## Dataset

The dataset that I utilized for this task was the PISA 2012 dataset. PISA, specifically, is a "survey of students' abilities and information as they approach the finish of mandatory training. It's anything but a regular school test. As opposed to inspecting how well studentshave taken in the school educational program, it takes a gander at how well

Inside this datset we can discover data for around 510,000 students. For every one of these students, there are 636 answers which we can find in the segments. Of these, I chose to fight this dataset into a more reasonable dataset of 15167 students with 19 segments. These sections convey the accompanying data about every student: 

    - Country                                          
    - Student ID                                         
    - Gender                                           
    - Out-of-School Study Time - Homework              
    - Out-of-School Study Time - Guided Homework       
    - Out-of-School Study Time - Personal Tutor        
    - Out-of-School Study Time - Commercial Company    
    - Out-of-School Study Time - With Parent           
    - Learning Time - Mathematics                      
    - Learning Time - Test Language                    
    - Learning Time - Science                          
    - Average Math Score                               
    - Average Reading Score                            
    - Average Science Score                            
    - Average Total Score                              
    - Education - Father                                
    - Education - Mother                                
    - Out-of-School Study Time - Total                 
    - Learning Time - Total
    
    
    
    
    
    
## Outline of Discoveries

All through the investigation of the cleaned PISA dataset, I needed to investigate two inquiries: 

- Is there a connection between the measure of time an student devotes to learning and their score? 
- Are there contrasts in accomplishment dependent on gender or parental education levels?
    

When looking at the measure of time an student places into their examinations and the score they accomplished, there cut off up being essentially no association between the Learning Time - Total, the Out-of-School Study Time - Total, and every one of the Score measurements. This promptly indicated the appropriate response: there is no connection between time spent learning and a definitive score. By and by, I looked further into the factors that involved every one of these aggregates.


When separating the Learning Time variables, it became clear that Learning Time - Science was the variable that raised the Learning Time - Total. It had a normal positive relationship of 0.093 among it and the Score factors, and this is sufficient to arrange it as a feeble positive connection. When taking a gander at it all the more intently in the multivariate investigation, it turned out to be evident that the Learning Time - Science variable had this feeble positive connection just when it came to more significant levels of parental schooling.


With respect to the Out-of-School Study Time factors, practically every one of them showed a frail negative connection. The one variable that didn't show a frail negative relationship was Out-of-School Study Time - Homework. This variable really had a normal positive relationship of 0.237 among it and the Score factors. This demonstrated that in spite of the fact that Homework is a positive marker for an student's score, Out-of-School Study Time is in everyday not an awesome measurement for anticipating the accomplishment of an understudy's score.


With respect to whether there is a connection between the measure of time an student commits to learning and their score, I would need to say that the two factors of Learning Time - Science and Out-of-School Study Time - Homework are not sufficiently able to make an unmistakable end. Accordingly, I would say that the measure of time an student commits to learning doesn't have a reasonable connection with their score.


Concerning the part question of whether there are contrasts in accomplishment dependent on gender or parental education levels, the appropriate responses are all the more clear. Albeit the sum was higher of students with parents who have higher educational levels, an example was extremely clear with what was normal. It is obvious from the information in this dataset that the more education a parent has, the almost certain the kid is to have a higher score. There are, obviously, anomalies for each gathering, however the normal would in general increment. That is anyway until either the mother or the fathers achieved upper secondary education. Starting there on, the score levels among the student's Average Total Score. We can, by the by say that parental level of education has a positive connection with the Average Total Score.

Then again, the second 50% of this inquiry didn't have such a distinction. Truth be told, from every one of the plots noticed, it appears as though gender  doesn't assume a part in the Score an student is probably going to get. There was anyway once special case. There was a slight benefit for female students when it went to the Average Reading Score. In any case, past that, the males and females performed correspondingly.

    
## Keys for Presentation    
    
For the introduction, I will investigate the focuses I talked about above with perceptions. Specifically, I will show the connection between the Scores, Learning Time, and Out-of-School Study Time factors to more readily respond to the subject of there a connection between the measure of time an student devotes to learning and their score. This will be finished with correlational plots and relapse plots.

I will at that point keep on responding to whether or not there contrasts in accomplishment dependent on gender or parental education levels. First this will be cultivated by noticing a pointplot that holds the data on both the mother's and father's level of education and the Average Total Score that is combined with that level.I will at that point keep taking a gander at this information from the viewpoint of a boxplot, yet a correlation between genders will likewise be remembered for this examination.