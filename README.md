<img src="https://github.com/rladies/starter-kit/blob/master/logo/R-LadiesGlobal_RBG_online_LogoWithText_Horizontal.png" data-canonical-src="https://github.com/rladies/starter-kit/blob/master/logo/R-LadiesGlobal_RBG_online_LogoWithText_Horizontal.png" width="300" height="100" />

# @WeAreRLadies: The R-Ladies RoCur  
    
## About  
  
The **[R-Ladies RoCur (Rotating Curation)](https://twitter.com/WeAreRLadies)** is a twitter handle that will feature an awesome R-Lady each week. This account is run by R-Ladies Global.      
  
   
## Objectives  
  
1. To encourage and maintain Twitter engagement within the R-Ladies community.    
2. To spotlight female and minority genders (including but not limited to cis/trans women, trans men, non-binary, genderqueer, agender) and their great work in R.   
  
## How It Works  
  
Every week, a different R-Lady takes over our twitter account to talk about the work they do in R. Featured curators come from a diversity of professions and have a range of experiences in R, from novice to expert.  
  
If you are interested in becoming a curator, see our [Be a Curator](#curating) section and [sign up here](https://goo.gl/forms/bQ7mHQDXrNHXEZCl2).  
  
Check out [@WeAreRLadies](https://twitter.com/WeAreRLadies) every Monday for a new curator!    
  

***  
  
  
## Curator Schedule  
  
Here is the current schedule of featured curators.  
  
  
```{r, echo=FALSE, eval=TRUE}
library(dplyr)
library(kableExtra)
schedule <- as_tibble(read.csv("files/Rocur_Schedule.csv",stringsAsFactors = FALSE))
# schedule_df <- data.frame(read.csv("Rocur_Schedule.csv",stringsAsFactors = FALSE))

schedule$Twitter <- paste0("[", schedule$Twitter, "](", schedule$handle_URL, ")")

kable(schedule[,1:4]) %>%
  kable_styling(bootstrap_options = "striped", full_width = F, position = "left")
```
  
  
***  
  
  
## Be a Curator! {#curating}  
  
We are always looking for R-users to be a featured curator for our account! Everyone is welcome; R-Ladies encourages R-users of all professional backgrounds and experience levels to curate this account. Additionally, individuals do not need to be affiliated with R-Ladies to curate. Featured curators must meet the following criteria:  
  
* Curators must identify as female or non-binary.  
* Curators do not need to be affiliated with R-Ladies; however, curators need to register in the [R-Ladies directory](https://rladies.org/directory/) if they haven’t yet   
* Curators must be individuals (i.e. an R-Ladies Chapter cannot be a featured curator; however, an organizer from a local chapter may curate and tweet about chapter events)   

### Curator Sign Up  
  
Individuals may sign up to be a curator via **[this form](https://goo.gl/forms/bQ7mHQDXrNHXEZCl2)**.   
  
  
* They will be asked to provide a first and second choice.    
* Curatorship begins each Monday at 7:00 AM ET and ends the following Saturday at 12:00 PM ET.   
* Administrators will make all efforts to honor all scheduling requests but may ask that you be flexible as the administrators need to coordinate multiple schedules.  
* Administrators will contact you to schedule the week you will curate.  
  
   
  

  



  

