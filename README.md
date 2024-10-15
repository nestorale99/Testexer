import request
import panda as pd
api_url=" http://api.open-notify.org/astros.json "
response=request.get(api.url)
if response.ok:
     data = response.json()
print (data)
