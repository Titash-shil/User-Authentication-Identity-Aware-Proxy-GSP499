# User Authentication: Identity-Aware Proxy || [GSP499](https://www.cloudskillsboost.google/course_templates/645/labs/464887) ||

# # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

* ### Run the following Commands in CloudShell
```
gcloud auth list

gcloud config list project

gsutil cp gs://spls/gsp499/user-authentication-with-iap.zip .

unzip user-authentication-with-iap.zip

cd user-authentication-with-iap

gcloud services disable appengineflex.googleapis.com

cd 1-HelloWorld

sed -i 's/python37/python39/g' app.yaml

#!/bin/bash

deploy_function() {
  gcloud app deploy
}

deploy_success=false

while [ "$deploy_success" = false ]; do
  if deploy_function; then
    echo "Function deployed successfully."
    deploy_success=true
  else
    echo "Retrying, please subscribe to Qwiklab_Explorers_TS (https://www.youtube.com/@Titashshil)..."
    sleep 10
  fi
done

cd ~/user-authentication-with-iap/2-HelloUser


sed -i 's/python37/python39/g' app.yaml

#!/bin/bash

deploy_function() {
  gcloud app deploy
}

deploy_success=false

while [ "$deploy_success" = false ]; do
  if deploy_function; then
    echo "Function deployed successfully."
    deploy_success=true
  else
    echo "Retrying, please subscribe to Qwiklab_Explorers_TS (https://www.youtube.com/@Titashshil)..."
    sleep 10
  fi
done

cd ~/user-authentication-with-iap/3-HelloVerifiedUser

sed -i 's/python37/python39/g' app.yaml

#!/bin/bash

deploy_function() {
  gcloud app deploy
}

deploy_success=false

while [ "$deploy_success" = false ]; do
  if deploy_function; then
    echo "Function deployed successfully."
    deploy_success=true
  else
    echo "Retrying, please subscribe to Qwiklab_Explorers_TS (https://www.youtube.com/@Titashshil)..."
    sleep 10
  fi
done

LINK=$(gcloud app browse)

LINKU=${LINK#https://}

cat > details.json << EOF
{
  App name: IAP Example
  Application home page: $LINK
  Application privacy Policy link: $LINK/privacy
  Authorized domains: $LINKU
  Developer Contact Information: aranyakskill1234@gmail.com
}
EOF
cat details.json
```
# Note :- 
* ### Go to Task 1 > Point No.2 > Check region > select numeric value in cloudshell (your provided region in lab instructions) 
* ### Provide your confirmation type (in clodshell): Y and Enter (follow same process 3 times)
* # Follow next all steps from video carefully...

# Congratulations ..!! You completed the lab shortly..😃💯

# *Well done..!* 👏

# Thank you for visiting.... :) 🗯️

# [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)




