from service import app 

@app.route("/")

def index():
  return "hello flask"

@app.route("/counter")
def get_counter():
  global counter 
  counter += 1 
  return dict(counter=counter)

def reset_counter():
  global counter
  if app.testing:
     counter = 0
