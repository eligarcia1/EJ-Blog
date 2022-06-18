# Access to Green Spaces through an Environmental Justice Lens

### Introduction

This blog will explore different maps of the built environment, and how these maps can be improved and used as social justice interventions.

My research interest is on accessibility to green spaces in Oakland. Minimal research has been done on accessibility to green spaces in Oakland, most environmental justice maps have focused on pollution burden in the area. 

I want to discuss how the built environment's relation to helping mitigate environmental hazards like pollution, but also other ways the built environemnt affects community health and the importance of access to green spaces.

Access to green spaces for marginalized communities is both a social justice and environmental justice intervention that helps community health and wellbeing.

### Cumulative Impact Map of Oakland

![image](https://user-images.githubusercontent.com/89550308/174424487-4b0580cf-8cee-4e20-ad84-f6c3e52bc004.png)
Source: CEJA

This map of Oakland uses an analysis of CalEnviroScreen 1.0
CalEnviroScreen has been updated to CalEnviroScreen 4.0 since this map has been made.

This map describes cumulative impacts as "a technical term to describe the lived reality in many low-income communities and communities of color." These impacts include economic and social stress and well as pollution burden.

![image](https://user-images.githubusercontent.com/89550308/174424459-0616bbfa-b0e2-4c21-9069-dc42f8972d7d.png)
Source: CEJA

This tool was made in 2012, and has inspired many tools that have come along afterwards including ones made for future versions of CalEnviroScreen.
I really like that this tool goes really in depth into hazards down to the street level. The map above is of Downtown Oakland going into East Oakland. This area has a lot of missing data, but overall it is seen that the cumulative impact in the area is high along the Oakland Flats, especially near the highway. It is also seen that the Oakland Hills has less of a cumulative impact score.


![image](https://user-images.githubusercontent.com/89550308/174424613-12947729-9a2b-4502-8896-1e0168c7ebcf.png)
Source: CEJA

The map above shows deep East Oakland off of Hegenberger. I have a personal connection to the area as I lived there right be Coliseum BART Station. The cumulative impact tool is great for maybe beginning to narrowdown some areas that need intervention, but I believe that this tool also misses a lot of local contexts and can sometimes seem minimizing to the communities that suffer from the highest scores of cumulative impact.

Also since it's so brief and covers so many different issues (like housing insecurity, pollution, etc.) it is difficult to see what problems need to be tackled exactly in the area. Each community has different needs and stories, even from block to another block.

I believe local contect matters and that cumulative impact tools sometimes can seem daunting to not only planners, but community members themselves.

The quantifying of suffering is a bit dark. 

The quantifying of suffering without an intervention strategy/method is even darker.

### Mapping for Environmental Justice

The cumulative impact mapping tool was a tool that can begin to narrow areas that need environmental justice interventions. Mapping for environmental justice interventions is something that can and will look different.

Environmental justice interventions need to be community based and relevant.

For GIS and mapping tools to help communities make decisions, I believe there needs to be direction and a plan to advocate for. 

Having an environmental justice lens for community change can be powerful, and also can create lots of excitement, optimism, and renewed community investment.

I believe that there should be optimism in mapping for environmental justice interventions along with the community context.

### Next Steps

I will be creating a map that analyzes the accessibility to green spaces in Oakland.

Some missing parts of the cumulative impacts maps were about the actual built environment. How are the areas zoned? What is the history of this built environemnt? Where are the green spaces? How can communties intervene with cumulative impacts? Who _really_ are the people that live there (some local narratives)?

For the map itself I want to use CalEnviroScreen 4.0, terrain layers, and also local knowledge. 

For the local knowledge I will conduct a handful of interviews but also gather data from social media platforms.

To find the quantifiable access to green spaces in Oakland I will use the Analysis tool in ArcGIS. I will summarrize the areas around green spaces by how accessible they are by walking. 

```markdown
The way to summarize this information in ArcGIS requires me to: 
1. Aggregate Points calculates statistics about points that fall within specified areas.
2. Join Features transfers attributes from one layer or table to another based on spatial and attribute relationships.
3. Summarize Nearby calculates statistics for features and their attributes that are within a specified distance.
4. Summarize Within calculates statistics for area features and attributes that overlap each other.
6. Summarize Center and Dispersion calculates central features and directional distributions.
```
I hope to use local knowdledge in the areas connected to the green spaces as well as areas that are disconnected. 

Local knowledge is important to me in this project because I also want to know if even if residents are in walking distance do they have struggles accessing the park and how we can work to make it more accessible to people.

Thank you for reading the blog!
