# Coursera_Capstone - Pinpoint Perfect Parish
This repository is for the Capstone Project of the Coursera IBM Data Science Certificate

Imagine, you want to visit or relocate to Porto City (Portugal). Which district would you choose for a stay? Not far from the ocean? Or, perhaps, you dislike noise, winds and gulls, so you prefer to stay neither by the shore, nor in the City Centre? Anyway, you probably want to know, how districts of the City differ from each other and which are similar.

- Project P.pdf            - Project presentation
- demo.html             - Demo result for final part of Capstone work
- Project_P report.pdf         - Full report
- Project P.ipynb           -  Main notebook

Notes:
1. In Toronto lab I use British spelling for 'Neighbourhood', pay attention, if you use a part of this code
2. For security purpose, I put API credentials into separate module map_api.py,
the code inside map_api.py is as follows:

class mapquest(object):  
   """mapquest api: key, secret"""  
   def \_\_init\_\_(self):  
       """Constructor"""  
       self.key = key  
       self.secret = secret  
          
class foursquare(object):  
   """Foursquare api: key, secret, version"""  
   def \_\_init\_\_(self):  
       """Constructor"""  
       self.id = id   
       self.secret = secret  
       self.version = '20190405'  
        
