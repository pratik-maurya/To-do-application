# Steps

# Step 1 create an angular project without or with rouitng. using #command 
  ng new toDoApp
# Step 2 install the json server using below command
  npm install -g json-server
# Step 3 create dashboard component, crud services and task class 
  using command 1) ng g c dashboard
                2) ng g s crud
                3) ng g class task
# Step 4 copy and pest the code as given above folder structure 
# start the json server
  json-server -watch db.json
  it will run on port 3000 and create and db.json file.
# Step 5 run both the json server and our angular to do application on browser.
