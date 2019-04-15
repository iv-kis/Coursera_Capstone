# Coursera_Capstone
This repository is for the Capstone Project of the Coursera IBM Data Science Certificate

Notes:
1. In toronto_geo lab I use British spelling for 'Neighbourhood', pay attention, if you use a part of this code
2. In toronto_geo lab for security purpose, I put API credentials into separate module map_api.py
the code inside map_api.py is as follows:

class mapquest(object):
    """mapquest api: key, secret"""
    def __init__(self):
        """Constructor"""
        self.key = <key>
        self.secret = <secret>
        
class foursquare(object):
    """Foursquare api: key, secret, version"""
    def __init__(self):
        """Constructor"""
        self.id = <id>
        self.secret = <secret>
        self.version = '20190405'
        
